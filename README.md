# Oefening: CSS Flexbox – soorten dennebomen

### Beschrijving
In deze opdracht ga je een overzichtspagina maken met verschillende soorten dennebomen. Je gebruikt CSS Flexbox om de boomsoorten flexibel uit te lijnen en overzichtelijk te presenteren.

### Instructies

1. Ga naar GitHub Classroom en accepteer de opdrachtlink die je van de leerkracht hebt ontvangen. Hierdoor wordt een persoonlijke repository voor deze opdracht aangemaakt.

2. Clone de repository naar je computer en open het project in **WebStorm**. Zorg dat de projectmap correct is opgeslagen op je Google Drive.

3. Controleer of de repository de volgende map- en bestandsstructuur heeft:
   - `index.html`
   - `assets/css/style.css`
   - `assets/img/` (optioneel, voor eventuele afbeeldingen van verschillende soorten dennebomen).

4. Open `index.html` en voeg de basis HTML-structuur toe. Gebruik uitsluitend **semantische tags** om de pagina overzichtelijk en toegankelijk te houden.

5. Voeg in de `head`-sectie een `<link>` toe om `style.css` te koppelen.

6. Voeg in de `<body>`-sectie de volgende elementen toe:
   - Een `<header>` met een `<h1>`-element met de tekst "Soorten Dennebomen".
   - Een `<section>` waarin de verschillende soorten dennebomen worden weergegeven. Geef deze `<section>` de klasse `tree-container` om het als flex-container in te stellen.
   - Voeg binnen de `tree-container` een reeks `<article>` elementen toe, elk voor een andere denneboomsoort. Elk `<article>` bevat:
     - Een `<h3>`-element met de naam van de denneboomsoort, zoals "Grove Den", "Zwarte Den", "Douglasspar", of "Blauwspar".
     - Een `<p>`-element met een korte beschrijving van de boomsoort.
   - Voeg een `<footer>` toe met een eenvoudige tekst, bijvoorbeeld "Geïnspireerd door de natuur".

7. Open `assets/css/style.css` en voeg CSS toe om een flexbox-layout te creëren:
   - Stel `.tree-container` in als een flex-container met:
     - `display: flex`
     - `flex-wrap: wrap` zodat de artikelen naar een nieuwe rij gaan wanneer er te weinig ruimte is.
     - `justify-content: space-around` om een nette ruimteverdeling te creëren.
     - `gap: 20px` om een beetje afstand tussen de artikelen toe te voegen.
   - Style elk `<article>` element in `.tree-container`:
     - Geef een vaste breedte van 200px.
     - Voeg een zachte schaduw toe met `box-shadow` voor een subtiele visuele scheiding.
     - Stel `text-align: center` in om de inhoud te centreren.
     - Voeg `padding` toe om ruimte rond de inhoud te creëren en alles overzichtelijk te houden.

8. Test de pagina in de browser om te controleren of de boomsoorten netjes uitgelijnd zijn en de layout goed werkt.

9. Controleer je HTML-code op validiteit met een HTML-validator om ervoor te zorgen dat de code semantisch correct is.

10. **Inleveren**:
    - Werk in je GitHub Classroom-repository en commit regelmatig. **Maak minimaal vijf commits** om je voortgang te laten zien. Gebruik duidelijke omschrijvingen voor elke commit.
    - Push je wijzigingen naar GitHub zodat de repository up-to-date is.
    - Controleer of de repository correct is gesynchroniseerd en volledig is.

---

### CSS Flexbox Eigenschappen

- `display: flex`
- `flex-wrap`
- `justify-content`
- `gap`

Veel succes met deze oefening!
