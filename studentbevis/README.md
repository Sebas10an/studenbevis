# Studentbevis – skoleprosjekt

Dette er kildekoden til versjon 1.2 av prosjektet.

## Redigere
Åpne mappen i en teksteditor, for eksempel Visual Studio Code.
- index.html: innhold, utseende (CSS) og funksjonalitet (JavaScript).
- manifest.webmanifest: innstillinger for installasjon som webapp.
- sw.js: mellomlagring for bruk uten nett.
- icon.svg: appikon.

## Kjøre lokalt
Med Python installert, åpne en terminal i mappen og kjør:

    python -m http.server 8000

Åpne http://localhost:8000 i nettleseren. Avslutt serveren med Ctrl+C.
For enkel visning kan index.html også åpnes direkte i nettleseren, men service worker og installasjon som webapp krever localhost eller HTTPS.

## Oppdateringer
Ved endringer i en tidligere installert versjon: øk CACHE-versjonen i sw.js, slik at gamle mellomlagrede filer erstattes.
Endringer i denne nedlastede kopien oppdaterer ikke automatisk den publiserte appen.
