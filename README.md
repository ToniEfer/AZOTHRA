# MISTIC

Mistyczna gra logiczna: 3 przenikające się okręgi, obrót okręgu przesuwa elementy, 2 takie same łączą się (+1 poziom), 3 w rzędzie to Trójca (+2). Wyższe elementy = wyższy stopień wtajemniczenia.
Prototyp HTML5, instalowalny na Androidzie jako aplikacja (PWA), działa offline.

**Gra:** adres GitHub Pages w Chrome na telefonie → menu ⋮ → *Zainstaluj aplikację* / *Dodaj do ekranu głównego*.

| Plik | Zawartość |
|---|---|
| `index.html` | cała gra (jeden plik) |
| `manifest.webmanifest`, `sw.js` | instalacja + cache offline |
| `version.json` | bieżąca wersja; gra ją sprawdza i proponuje odświeżenie |
| `icons/` | ikony aplikacji |

**Nowa wersja:** ten sam numer w `APP_VERSION` (index.html), `VERSION` (sw.js) i `version.json`, potem push.

© Toni — prototyp, wszelkie prawa zastrzeżone.
