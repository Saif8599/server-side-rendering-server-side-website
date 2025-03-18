# Bieb in Bloei - Stekjespagina

## Inhoudsopgave

- [Beschrijving](#beschrijving)
- [Gebruik](#gebruik)
- [Kenmerken](#kenmerken)
- [Installatie](#installatie)
- [Bronnen](#bronnen)
- [Licentie](#licentie)

## Beschrijving

De *Bieb in Bloei* stekjespagina is een dynamische webapplicatie waarmee gebruikers beschikbare stekjes kunnen bekijken en gedetailleerde informatie kunnen krijgen via een server-side rendered website. De toepassing maakt gebruik van **Express.js** en **dynamische routing** om de gegevens uit een **WHOIS API** te laden en weer te geven.

## Gebruik

De applicatie biedt:

- Een **stekjespagina** waar alle beschikbare stekjes worden weergegeven met een afbeelding en naam.
- Een **detailpagina** per stekje met uitgebreide informatie, zoals oorsprong, verzorgingstips en beschikbaarheid.
- **Server-side rendering (SSR)** om ervoor te zorgen dat de pagina's direct bij het laden de juiste inhoud tonen.
- Een **header met een ingebouwde navigatiebalk** en een **footer** voor een consistente gebruikerservaring.
- **Mobile-first ontwerp en responsiviteit**, zodat de pagina optimaal functioneert op zowel mobiele als desktopapparaten.

## Kenmerken

### Technologieën

- **Node.js & Express.js** – voor de server en routing.
- **LiquidJS** – als templating engine voor dynamische HTML-rendering.
- **WHOIS API** – voor het ophalen van gegevens over beschikbare stekjes.
- **Responsive design** – de pagina schaalt en past zich aan op verschillende schermformaten.

### Structuur

```
📁 server-side-rendering-server-side-website
│── 📂 views (Express routes + LiquidJS templates)
│── 📂 public (CSS, afbeeldingen, scripts)
│── server.js (Hoofdserverbestand)
│── package.json (Projectconfiguratie)
```

## Installatie

1. **Clone de repository:**
   ```bash
   git clone https://github.com/Saif8599/server-side-rendering-server-side-website.git
   cd server-side-rendering-server-side-website
   ```
2. **Installeer de dependencies:**
   ```bash
   npm install
   ```
3. **Start de server:**
   ```bash
   npm start
   ```
4. **Toegang tot de applicatie:**
   - Open een browser en ga naar: `http://localhost:8000`
   - De stekjespagina is te vinden op `/stekjes`
   - Een specifieke stekjesdetailpagina is te vinden op `/stekjes/:id`

## Bronnen

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [LiquidJS](https://liquidjs.com/)

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).

