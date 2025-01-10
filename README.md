# Czytelnik Biblii

Aplikacja do czytania Biblii z funkcją zamiany tekstu na mowę i śledzeniem przeczytanych wersetów, zaprojektowana, aby pomóc Ci w końcu skończyć Biblię.

![GUI Czytelnika Biblii](https://i.imgur.com/vLoN8Re.png)

## Funkcje
- **Tekst na mowę:** Czytaj wersety na głos dzięki wysokiej jakości zamianie tekstu na mowę.
- **Śledzenie wersetów:** Oznaczaj wersety jako przeczytane i śledź postępy w czytaniu.
- **Tworzenie plików MP3:** Twórz pliki MP3 dla wybranych wersetów, aby słuchać ich na telefonie.
- **Notatki do rozdziałów:** Zapisz i wczytaj notatki do każdego rozdziału, aby ulepszyć naukę.
- **Dostosowywanie:** Dostosuj rozmiar tekstu i preferencje głosowe.
- **Pomiń przeczytane wersety:** Pomiń wersety, które już przeczytałeś, aby skupić się na skończeniu Biblii.

## Instalacja

### Wymagania wstępne

1. **Python 3.11.9:**
- Pobierz instalator z [Python 3.11.9](https://www.python.org/downloads/release/python-3119/).
- Uruchom instalator i upewnij się, że zaznaczyłeś pole wyboru „Dodaj Pythona do PATH” przed kliknięciem „Zainstaluj teraz”.

2. **ffmpeg 7.0.0.20240429:**
- Pobierz instalator z [ffmpeg 7.0.0.20240429](https://github.com/icedterminal/ffmpeg-installer/releases/tag/7.0.0.20240429).
- Uruchom instalator i postępuj zgodnie z instrukcjami.
- **Dodaj ffmpeg do PATH:**
- Otwórz menu Start i wyszukaj „Zmienne środowiskowe”.
- Kliknij „Edytuj zmienne środowiskowe systemu”.
- W oknie Właściwości systemu kliknij przycisk „Zmienne środowiskowe”.
- W oknie Zmienne środowiskowe znajdź zmienną „Ścieżka” w sekcji „Zmienne systemowe” i kliknij „Edytuj”.
- Kliknij „Nowy” i dodaj ścieżkę do katalogu „bin” instalacji ffmpeg (np. „C:\ffmpeg\bin”).
- Kliknij „OK”, aby zamknąć wszystkie okna.

3. **Git:**
- Pobierz i zainstaluj Git z [Git dla Windows](https://gitforwindows.org/).
- Postępuj zgodnie z instrukcjami instalacji, aby upewnić się, że Git został dodany do PATH systemu.

### Kroki

1. **Klonuj repozytorium:**
- Otwórz wiersz poleceń lub terminal.
- Przejdź do katalogu, w którym chcesz sklonować repozytorium.
- Uruchom następujące polecenie, aby sklonować repozytorium:
```sh
git clone https://github.com/sleepdeprived3lovesGod/kjv-bible-reader.git
```

2. **Przejdź do katalogu projektu:**
- Przejdź do katalogu projektu:
```sh
cd kjv-bible-reader
```

3. **Uruchom instalatora:**
- Uruchom plik `windows_install.bat`, aby skonfigurować środowisko wirtualne i zainstalować zależności:
```sh
windows_install.bat
```
- Może być konieczne uruchomienie go jako Administrator, aby upewnić się, że wszystkie uprawnienia są poprawnie ustawione.

4. **Uruchom aplikację:**
- Uruchom plik `start.bat`, aby uruchomić Bible Reader:
```sh
start.bat
```

## Użycie

- **Nawigacja:**
- Użyj menu rozwijanych, aby wybrać księgę, rozdział i werset, który chcesz przeczytać.
- Kliknij przycisk „Czytaj”, aby usłyszeć werset odczytany na głos.
- Użyj przycisku „Wstrzymaj”, aby wstrzymać czytanie.
- Kliknij przycisk „Następny nieprzeczytany”, aby przejść do następnego nieprzeczytanego wersetu.

- **Dostosowanie:**
- Dostosuj rozmiar tekstu za pomocą przycisków „+” i „-”.
- Zmień głos za pomocą menu rozwijanego głosu.
- Pomiń przeczytane wersety, zaznaczając pole wyboru „Pomiń przeczytane wersety”.

- **Notatki:**
- Napisz i zapisz notatki dla każdego rozdziału, korzystając z sekcji notatek.
- Skopiuj notatki do schowka, korzystając z przycisku „Kopiuj notatki”.

- **Tworzenie MP3:**
- Kliknij przycisk „Utwórz MP3”, aby utworzyć plik MP3 dla wybranego zakresu wersetów.

- **Opcje resetowania:**
- Zresetuj historię rozdziałów, notatki, preferencje lub wszystkie dane za pomocą przycisków resetowania.

## Prawa autorskie

KJV Wersja Króla Jakuba jest domeną publiczną wszędzie poza Wielką Brytanią. Jeśli używasz jej w Wielkiej Brytanii, upewnij się, że masz pozwolenie od korony.

## Rozwiązywanie problemów

### Typowe problemy

- **Nie znaleziono Pythona:**
- Upewnij się, że Python 3.11.9 jest zainstalowany i dodany do ścieżki PATH systemu.
- Sprawdź to, otwierając wiersz poleceń i wpisując `python --version`. Powinien wyświetlić numer wersji.

- **Nie znaleziono ffmpeg:**
- Upewnij się, że ffmpeg 7.0.0.20240429 jest zainstalowany i dodany do ścieżki PATH systemu.
- Sprawdź to, otwierając wiersz poleceń i wpisując `ffmpeg -version`. Powinien wyświetlić numer wersji.

- **Moduł nie został znaleziony:**
- Uruchom plik `windows_install.bat`, aby zainstalować wszystkie zależności.

- **Inne problemy i aktualizacja ze starszych wersji:**
- Usuń `config.ini` i pozwól mu utworzyć nowy.
