# Server-Side Website

Ontwerp en ontwikkel een server-side website voor een opdrachtgever

De instructie vind je in: [INSTRUCTIONS.md](https://github.com/fdnd-task/server-side-rendering-server-side-website/blob/main/docs/INSTRUCTIONS.md)


## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Gebruik](#gebruik)
  * [Kenmerken](#kenmerken)
  * [Installatie](#installatie)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
Dit project is gemaakt voor Frankendael, een botanische tuin in Amsterdam. De webapp is een digitale veldgids waarmee parkbezoekers via hun telefoon nieuws kunnen lezen over planten in het park, de plantencollectie kunnen bekijken en meer informatie kunnen opzoeken over specifieke planten.
De app werkt volledig server-side met dynamische data uit de Directus API van FDND Agency. Pagina's worden opgebouwd op de server op basis van de data die uit de API komt, en als HTML teruggestuurd naar de browser. Hierbij is vooral gewerkt met URL-structuur, routes en het verwerken van data.

- 🌐 Live demo: https://server-side-rendering-server-side-website-gykj.onrender.com/

## Gebruik
Als gebruiker kom je eerst op de homepagina met een overzicht van veldnieuwsartikelen. Je kunt navigeren naar de nieuwspagina om daar het laatste nieuws te bekijken, waar de volledige tekst en bijbehorende informatie te zien is.

De pagina’s worden dynamisch geladen, zodat de content altijd actueel is. De URL past zich aan aan de pagina die je bezoekt, wat navigatie en delen van pagina’s eenvoudig maakt.

## Kenmerken
De applicatie is gebouwd met Node.js en Express voor server-side routing. Afhankelijk van de URL wordt bepaald welke pagina en data geladen wordt.

Data wordt opgehaald uit de Directus API en dynamisch verwerkt met een templating engine, zodat nieuwsartikelen correct worden weergegeven. De focus lag op het werken met routes, GET requests en het renderen van dynamische content in HTML.

## Installatie
Wil je als developer met deze code werken, volg dan deze stappen:

Clone de repository:
git clone https://github.com/hebaahx/server-side-rendering-server-side-website

Installeer de benodigde packages:
npm install

Start de server:
npm start

Open je browser op:
http://localhost:8000

De app werkt direct met data uit de Directus API, dus er is geen eigen database nodig.

## Bronnen

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
