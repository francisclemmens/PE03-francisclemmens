# Algemene opdrachtomschrijving

## Situatieschets

Een zelfstandige (kruidenier, bakker, nagelstyliste, …) vraagt je om een website te bouwen waarop algemene info te vinden is en een webshop.
De volgende pagina’s zijn noodzakelijk:

- Indexpagina: welkomstpagina met **algemene informatie** over de diensten en een **product in de spotlight**.
- Webwinkel: een pagina met een overzicht van een 8- à 10-tal producten in 2 categorieën met een korte beschrijving en prijs per product.

## Keuze onderwerp

Vóór je aan de opdracht begint, dien je eerst je onderwerp van je werk in (zie opdracht in Leho);

- Houd er rekening mee dat je het bovenstaande moet kunnen verwezenlijken.
- Dubbele onderwerpkeuzes worden niet toegelaten. Elke student maakt dus een uniek project.
- Goedkeuring project:
  - Op de opdrachtpagina (Leho) zal je een lijst terugvinden met je naam erin. Indien het project goedgekeurd wordt, verschijnt je gekozen onderwerp in de lijst. Andere studenten kunnen dit onderwerp dan niet meer kiezen.
  - Indien je project afgekeurd wordt, word je hiervan op de hoogte gebracht via de e-mail.

- Eventueel kan je een onderwerp kiezen uit deze lijst (ook bij keuze van een item uit deze lijst dien je een voorstel in!):

> Apotheker, Bierbrouwer, Chocolatier, Drukker, Elektricien, Fruitteler, Garagist, Hotelier, Juwelier, Loodgieter, Makelaar (huizen), Nagelstyliste, Opticien, Reisagent, Schoenmaker, Tuinman, Uurwerkwinkel, Viswinkel, Wijnboer, Antiquair, Bloemist, Fietsenhandelaar

**Studenten die geen onderwerp doorgave tegen de deadline zullen een willekeurig onderwerp toegekend worden.**

## Indienen

Je laatste commit voor de deadline in Github Classrooms wordt verbeterd. Met alle wijzigingen via latere commits wordt geen rekening gehouden.

>**Vergeet niet om regelmatig te committen en pushen naar je repository.<BR/>Controleer of je project daadwerkelijk volledig online staat.<BR/>Enkel wat online staat wordt geëvalueerd!**

# Technische uitwerking

## Technische (algemene) vereisten

Hieronder vind je een uitgebreide taakomschrijving in de vorm van een opsomming. Tijdens de ontwikkeling van je pagina kan je de uitgevoerde taken afvinken.

- [ ] Je maakt een **responsive layout** met behulp van een **CSS grid** voor de algemene layout van de pagina en gebruikt die consistent op alle pagina’s. Je website ziet er dus zowel op mobile als desktop als goed uit. Voor mobile werk je met een verticale schikking, zowel voor de start- als de productenpagina.
- [ ] De productenlijst(en) wordt vorm gegeven met behulp van een **CSS flexbox**.
- [ ] Gebruik de HTML5 semantische tags waar gepast (bv. headers, footers, main, section, article,…)
- [ ] Organiseer je CSS, figuren en html-bestanden in een **ordelijke mappenstructuur**.
- [ ] Alle webpagina’s zijn in geldige HTML5 opgebouwd (**valideer zelf via https://validator.w3.org/#validate_by_input**).
- [ ] De webpagina’s zijn cross-browser en vertonen in alle moderne browsers een consistente weergave. Test in Chrome, Firefox en Edge.
- [ ] Voorzie een **navigatiebalk** door gebruik te maken van een lijst.
Het moet duidelijk zijn in de navigatiebalk op welke pagina de gebruiker zich bevindt.
- [ ] Je website is voorzien van een reclameboodschap met tekst en/of een afbeelding die een bescheiden **animatie** heeft.
- [ ] Op een vaste plaats van de pagina met producten staat een **chatknop**. Deze knop hoeft niet te werken, maar ze is steeds zichtbaar op dezelfde plaats, ook al wordt er gescrolled.
- [ ] Wanneer er over de chatknop gehovered wordt, dan vindt er daarop een duidelijk zichtbare **transitie** plaats.
- [ ] Onderaan elke pagina staat een **disclaimer** :<BR>“Dit is een virtuele oefenfirma. Informatie, transacties en goederen op deze website zijn fictief en hebben louter educatieve doeleinden.”
- [ ] Plaats volgende **copyrighttekst** op elke pagina: “© 2022 Howest Brugge”.

## Vereisten design

De website is de online identiteit van het bedrijf en vereist dus een professionele look en een consistente huisstijl. Behalve de inhoud moet er dus ook een goed design gemaakt worden:

- Zorg voor een consistent kleurenschema. Gebruik deze kleuren op strategische plaatsen zodat de gebruiker overal de huisstijl herkent. Het is uiteraard toegestaan om extra kleuren toe te voegen. (wit, donkergrijs, zwart of kleuren uit een zelfgemaakt palet : http://colorschemedesigner.com)
- Maak een consistente look & feel op elke pagina. Hoewel de inhoud van elke pagina anders is, moeten deze echt wel bij elkaar passen.
  - de navigatie moet op dezelfde plaats terug te vinden zijn
  - layouts zijn gelijkaardig
  - er wordt weinig of niet afgeweken van het gekozen kleurenschema.
- Het overige wordt overgelaten aan jouw creativiteit. Even geen inspiratie? Bekijk jouw favoriete sites eens goed of Zoek gratis sjablonen online. Denk eraan dat sjablonen aanpassen vaak tijdrovender is dan zelf *'from scratch'* te beginnen.

# Inhoudelijke uitwerking

## Indexpagina

Dit is de welkomstpagina die volgende informatie bevat:

- Verwelkoming op de site
- Twee à drie alinea's beschrijvende tekst van max. 40 woorden mbt de winkel of haar producten.
- Gebruik passende semantische elementen ifv de outline en de semantiek van bepaalde woorden/stukken tekst.
- Spotlight: Kies een favoriete product uit de lijst en plaats het in de “spotlight” op de indexpagina. Link deze door naar de desbetreffende plaats op je productenpagina (ankerpunt).
- Gebruik een grid om de pagina in verschillende delen op te delen. Beheer de schikking adhv grid-areas.

## Productenpagina

Op deze pagina kunnen potentiële klanten de aangeboden categorieën in detail bekijken. Het is dus enorm belangrijk dat de categorieën zeer professioneel en overzichtelijk worden gepresenteerd.

- Er wordt een 8- à 10-tal producten getoond in 3 categorieën met een korte beschrijving en prijs per product. 
Zoek hiervoor de nodige informatie online. (afbeeldingen, beschrijvingen,…).
- De producten staan binnen een flexbox. Het product zélf is dus een flex item.

> :warning: **Er dient geen “winkelkar” systeem of iets dergelijks ingebouwd te worden.**

> :warning: **Een zeker volume is noodzakelijk om je vaardigheden te demonstreren, maar weet dat dit niet het belangrijkste criterium is voor je score. Houd je aan de gevraagde volumes**
