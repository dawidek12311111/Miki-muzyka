# Muzyczne Klocki

Prosta aplikacja dla dzieci do tworzenia muzyki z kolorowych klocków, w stylu dawnego eJay.

## Jak grać

- Wybierz ścieżkę: Bębny, Bas, Melodia, Akordy albo Efekty.
- Stuknij klocek, żeby usłyszeć jego dźwięk.
- Stuknij puste pole na ścieżce, żeby położyć tam klocek. Drugie stuknięcie go zabiera.
- Gumka usuwa klocki z dowolnej ścieżki.
- Zielony przycisk gra piosenkę w pętli. Spacja też działa.
- Stuknięcie nazwy ścieżki wycisza ją.

Wszystkie dźwięki są w tej samej tonacji, więc każda kombinacja brzmi dobrze. Piosenka zapisuje się automatycznie w przeglądarce.

## Technika

Jeden plik `index.html`, bez bibliotek i bez plików z dźwiękami. Wszystkie dźwięki są generowane na żywo przez Web Audio API.

## Uruchomienie na GitHub Pages

1. Wrzuć `index.html` do repozytorium.
2. Settings → Pages → Branch: `main`, folder `/ (root)` → Save.
3. Po minucie strona działa pod adresem `https://TWOJA-NAZWA.github.io/NAZWA-REPO/`.
