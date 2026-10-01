# Hei, jeg er Nicolay

Jeg går andre året på Ingeniørvitenskap og IKT på NTNU i Trondheim. Ved siden av studiet bygger jeg ting som løser problemer jeg selv har kjent på, eller som folk rundt meg klager over. Det starter gjerne med «det må da gå an å gjøre dette enklere», og ender som et prosjekt jeg ikke klarer å legge fra meg.

## Hvordan jeg jobber

Jeg bruker mest tid før og etter selve kodingen. Først på å forstå problemet og finne ut hva løsningen egentlig må gjøre, så på å teste den mot ekte data og fikse det som ikke holder. Jeg liker å få noe opp og kjøre tidlig, og heller forbedre det underveis enn å planlegge meg bort. I hver README skriver jeg hva jeg har testet, og hvorfor ting er bygget som de er.

## Prosjekter

| Prosjekt | Hva det er | Teknologi | Det vanskeligste valget |
|---|---|---|---|
| [AnbudsRadar](https://github.com/Nicolaykopaas/anbudsradar) ([live demo](https://anbudsradar.streamlit.app/)) | Henter offentlige anbud fra Doffin og finner bedriftene som faktisk kan ta jobben | Python, pandas, Streamlit, Doffin- og Brreg-API | EU og Norge deler inn bransjer helt forskjellig, så jeg måtte lage min egen oversettelse mellom de to systemene |
| [Byggeradar](https://github.com/Nicolaykopaas/byggeradar) ([live demo](https://byggeradar.streamlit.app/)) | Samler nye byggetillatelser fra hele landet og sorterer dem etter fag | Python, Streamlit, egen adapter per kommune | GDPR gjør det ulovlig å sende reklame på e-post til privatpersoner, så jeg måtte tenke nytt rundt hvordan tipsene skal nå fram |
| [Pubgolf](https://github.com/Nicolaykopaas/norkartbedpress) ([live demo](https://nicolaykopaas.github.io/norkartbedpress/)) | Pubgolf-app for Trondheim sentrum: du sveiper på drinker som på Tinder, og appen lager en rute mellom barene med priser fra Pilsguiden | React, TypeScript, MapLibre, Norkart-kart og ruteberegner, Cloudflare Workers | En statisk GitHub Pages-side kan ikke holde en API-nøkkel hemmelig, så kartet og ruta går via en liten Cloudflare Worker som legger på nøkkelen |
| [adkiller](https://github.com/Nicolaykopaas/adkiller) | Chrome-utvidelse som blokkerer annonser i sju lag | JavaScript, Manifest V3 | Hvert nytt lag gjør sidene litt tregere, så jeg måtte finne ut hvor grensen går før det ikke lenger er verdt det |
| [Boligregnskap](https://github.com/Nicolaykopaas/boligregnskap) ([live demo](https://boligregnskap.onrender.com)) | Regnskap, skatteanslag og leieprisestimat for utleieboliger | Java 21, Spring Boot 3 | Holdt meg til en enkel fildatabase (H2) i stedet for en egen databaseserver, siden det bare er én bruker |

Akkurat nå jobber jeg også med en mobilapp for festivaler, som skal gjøre vakter, timeplaner og kontaktinfo enklere for artister, frivillige og ansatte. Den lager jeg sammen med en som kjenner bransjen fra innsiden.

## Teknologi

Mest Python og Java, men også TypeScript og JavaScript. Jeg har jobbet mye med Spring Boot, React, Streamlit og pandas, og liker best prosjekter der offentlige data, matching og språkmodeller møtes.

## Kontakt

nicolay.kopaas@gmail.com
