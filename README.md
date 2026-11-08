# Padelrunden

En enkel nettside for å spille **Americano** og **Mexicano** i padel. Alt ligger i én fil, `index.html`, uten byggesteg eller avhengigheter.

## Funksjoner

- Velg format, poeng per kamp (16/21/24/32) og antall baner
- Legg inn spillere (flere samtidig med komma)
- **Americano:** roterende makkere, med færrest mulig gjentatte makkere og motstandere
- **Mexicano:** første runde tilfeldig, deretter 1+4 mot 2+3 per bane etter tabellen
- Skriv inn poengene til ett lag, så fylles det andre laget ut automatisk
- Rettferdig pause: de som har stått over minst står over først, og kan få halve poeng for runden
- Live tabell sortert på poeng, seire og poengdifferanse
- Turneringen lagres i nettleseren (localStorage)

## Kjør lokalt

Åpne `index.html` i en nettleser.

## Publiser med GitHub Pages

Settings → Pages → Deploy from a branch → `main` / root.
