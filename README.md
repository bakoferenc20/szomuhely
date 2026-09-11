# Szóműhely – v0.1

Új német szavak első megtanulása mély kódolással. Az Anki előszobája: ami itt átmegy, az exportálható kártya lesz.

## Kipróbálás
- Böngészőben: nyisd meg az `index.html`-t (a beépített Bevezetés-fejezettel indul).
- Telefonra telepítve (PWA): tedd fel a mappát egy https helyre (pl. GitHub Pages), nyisd meg Chrome-ban, „Hozzáadás a kezdőképernyőhöz”. Utána offline is megy.
- Helyi kipróbálás: `python3 -m http.server 8000` a mappában, majd http://localhost:8000

## Fejezet hozzáadása
1. Készíts egy új `chapters/<id>.json`-t a `wirtschaft-01.json` szerkezetével (asztali előgenerálás).
2. Az appban: „Másik fejezet betöltése (JSON)”.

## Anki-import
Az export egy tabulátoros `.txt`. AnkiDroid → Importálás → fájl kiválasztása. A fejléc (`#deck column:3`) alapján a szavak a `Wirtschaft::Fachwortschatz` / `::Allgemein` alpaklikba mennek; a jegyzetek típusa a „Basic” (Front/Back).
