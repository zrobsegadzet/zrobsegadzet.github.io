# Zrób Se Gadżet — GitHub Pages

To jest gotowy statyczny eksport strony. Nie zawiera PHP, formularza serwerowego ani bazy danych.

## Publikacja

1. Utwórz repozytorium na GitHubie.
2. Wgraj całą zawartość tego folderu do głównego katalogu repozytorium — razem z plikami `.nojekyll` i `CNAME`.
3. Wejdź w **Settings → Pages** i wybierz publikację z gałęzi `main`, katalog `/root`.
4. W ustawieniach domeny OVH dodaj rekordy GitHub Pages wskazane przez GitHub. Plik `CNAME` ustawia domenę `zrobsegadzet.pl`; jeśli chcesz najpierw testować bez domeny, możesz go tymczasowo usunąć.
5. Po aktywacji sprawdź: stronę główną, każdą podstronę, zdjęcia oraz linki mailowe i WhatsApp.

## Zawartość

Strona zachowuje podstrony `galeria.html`, `firmy.html`, `instytucje.html`, `organizacje.html`, `okolicznosciowe.html`, `warsztaty.html`, `regulamin.html` i `polityka.html`. Kontakt odbywa się przez `zrobsegadzet@gmail.com`, telefon i WhatsApp — nie ma już formularza PHP zależnego od hostingu OVH.

## Dodawanie zdjęć

Zdjęcia znajdują się w katalogu `assets`. Nowe zdjęcie można dodać do tego katalogu, a następnie dopisać jego ścieżkę w kodzie źródłowym projektu przed kolejnym buildem.
