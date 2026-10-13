# Muzyczne Klocki

Aplikacja dla dzieci do tworzenia muzyki z kolorowych klocków, w stylu dawnego eJay. Działa w przeglądarce, można ją zainstalować na telefonie i używać bez internetu.

## Co jest w środku

- **Ekran powitalny**: „Cześć, [imię]!”, tańcząca postać i awatar dziecka, losowy bit, losowa scena, przyśpiewka z imieniem i „Tworzymy razem, [imię]!”.
- **164 klocki na 9 ścieżkach**: Bębny, Bas, Akordy, Melodia, Instrumenty, Głosy, Zwierzaki, Efekty, Moje dźwięki. Każda ścieżka ma kategorie: spokojne, skoczne, śmieszne. Wszystko gra w jednej tonacji.
- **8 tańczących postaci**: robot, kot, dinozaur, jednorożec, kosmita, pingwin, panda, rakieta.
- **Wideo z piosenką**: pionowe, poziome albo kwadratowe, 6 scen, tańcząca postać, klocki w rytm, konfetti na końcu.
- **Zapisywanie piosenek**, pobieranie muzyki jako .wav, własne nagrania z efektami (robot, chomik, potwór, echo).
- **Ustawienia dziecka**: imię, zdjęcie jako awatar, postać, kolor, nagranie imienia.
- **Panel rodzica** (przytrzymaj kłódkę 3 s, hasło **1234**): limity czasu, godziny grania, przerwy, głośność, uprawnienia, poziomy trudności, profile, statystyki, kopia zapasowa, wygląd, naklejki, pełny ekran, instalacja, zmiana hasła.

## Pliki

| Plik | Do czego |
|---|---|
| `index.html` | cała aplikacja |
| `manifest.json` | opis aplikacji do instalacji |
| `sw.js` | działanie bez internetu |
| `icon-192.png`, `icon-512.png`, `icon-maskable.png`, `apple-touch-icon.png` | ikonki |

## GitHub Pages

1. Wrzuć wszystkie pliki do głównego folderu repozytorium.
2. Settings → Pages → Branch: `main`, folder `/ (root)` → Save.
3. Po minucie strona działa pod adresem `https://TWOJA-NAZWA.github.io/NAZWA-REPO/`.

Dane (profile, piosenki, nagrania) są zapisane w przeglądarce na danym urządzeniu. Żeby je przenieść, użyj „Kopii zapasowej” w panelu rodzica.
