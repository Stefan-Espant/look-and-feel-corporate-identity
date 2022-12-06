# Handleiding voor partners Vervoerregio Amsterdam
<!-- Geef je project een titel en schrijf in één zin wat het is -->

## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
<!-- In de Beschrijving staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->
<!-- Voeg een mooie poster visual toe 📸 -->
<!-- Voeg een link toe naar Github Pages 🌐-->
De user story die ik koos luidde alsvolgt:
> Als gebruiker wil ik de webiste in een Donkere modus kunnen bekijken voor tijdens de donkere maanden

> Als gebruiker wil ik een terug naar boven kunnen vinden om gemakkelijker te navigeren
> 
<img width="1512" alt="Schermafbeelding 2022-12-06 om 12 15 50" src="https://user-images.githubusercontent.com/89298385/205898114-fb059be6-dd1a-4fc9-aca1-d9a2ed3b6a7e.png">
<img width="1512" alt="Schermafbeelding 2022-12-06 om 12 15 35" src="https://user-images.githubusercontent.com/89298385/205898109-0d31a687-4db2-4c80-bdfb-40cd51ee49b7.png">
<img width="1512" alt="Schermafbeelding 2022-12-06 om 12 18 39" src="https://user-images.githubusercontent.com/89298385/205898121-8533ff4d-7174-4b5b-ae4b-1a9fdd6a07fe.png">
<img width="1512" alt="Schermafbeelding 2022-12-06 om 12 18 01" src="https://user-images.githubusercontent.com/89298385/205898116-dd2740b9-10f0-43b3-9c9a-d03ac11c5107.png">


De sitemap begint op de landingspagina met een minimalistische opmaak. Het bestaat uit 3 onderdelen: een header, een main die is opgesplitst in 2 secties (de titel van het product en de aside met 4 hoofdcatergorieën).

https://stefan-espant.github.io/look-and-feel-corporate-identity// 

## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->
De sitemap is opgebouwd uit de 3 basistalen: HTML, CSS & Javascript.

### html
De html bestaat overal uit dezelfde indeling: een head en een body.

#### head
In de head worden 4 css bestanden in geladen die voor de style zorgen. Ook word er een favicon geladen voor in de tabbladen die snel weergeven dat het om de Toolgankelijk website gaat.

Dit zijn de linkjes naar de CSS:<br>
`<link rel="stylesheet" href="../styles/style.css" />`<br>
`<link rel="stylesheet" href="../styles/mobile.css" />`<br>
`<link rel="stylesheet" href="../styles/tablet.css" />`<br>
`<link rel="stylesheet" href="../styles/desktop.css" />`<br>

Dit is de link die de favicon projecteert:<br>
`<link rel="icon" type="image/png" href="./assets/va-favicon.png"/>`

#### body
De body bestaat overal uit dezelfde indeling: een header, een aside en een main element.

#### header
De header bevat de volgende 2 onderdelen: een logo en een balk die word verbonden door een vloeiende golf.<br> 
`<img id="logo" src="../assets/logo.png" alt="logo Vervoerregio Amsterdam"/>`<br>
`<div id="after-curve"></div>`

#### aside
De aside bestaat uit 4 knoppen die doorlinken naar de hoofdcatergorieën:<br>
`<a href="waarneembaar.html" class="categorie">`

#### main
In de main wordt alle content getoond en getoggled wanneer de gebruiker op een knop klikt.
Dit component bevat headings, tekst, links, afbeeldingen.

### css
Alle pagina's hebben een `scroll-behavior: smooth;` om vloeiend te scrollen.<br>
Ook heb ik alle klikbare elementen een `transition: 0.8s` gegeven om vloeiend en aangenaam van state te veranderen. Harde animaties wordt over het algemeen als grof beschouwd.

### javascript
Javascript heb ik toegepast op de volgende functies:
De `content-item` knoppen die de content laten weergeven in de main.

De contrast knop die de verhouding van kleurcontrasten verhoogd en zo aan de WCAG AAA-eisen voldoen.

De tekstvergroot knop die de tekst in de `main` vergroot tot 200%.

De funcitie om feedback te geven op de website en reactie hierop aan de gebruiker.

## Bronnen

Om het product te bouwen heb ik de volgende websites gebruikt voor antwoorden, voorbeelden en kennis.<br>
https://css-tricks.com<br>
https://developer.mozilla.org/en-US/<br>
https://stackoverflow.com<br>
https://whaa.dev

## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
