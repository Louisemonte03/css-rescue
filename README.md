# css-rescue-her

## week 1

### Week 1 11/05 - 17/05

**Wat heb ik gedaan?**
Deze week ben ik aan de gang gegaan met de herkansing voor CSS. Mijn vorige opdracht was een Silly walk en ik ga nu iets nieuws maken. Ik pakt de opdracht om de control panel te maken. Daarbij had ik als idee om een Apple Tv na te maken. Ik ga dus het scherm van de Apple Tv laten zien met de apps die daar bij horen. En ik ga de remote maken. Dat is nu het eerste idee dat ik heb. Daarvan heb ik de design al een soort van gemaakt. Het Alles is gescreven met code. Het totaal plaatje om de in de interactie werkend te maken moet nog lukken. Eerst ging ik beginnnen met het maken van de remote en daar van de stijling van. Daar gebruikte ik de grid methodes om zo alles op positie. Daarvoor gebruikte ik ook de Grid generator zodat ik precies kon zien waar ik bijvoorbeeld de bolltjes van de trackpad en de postitie van de knoppen kan neer zetten. Ook gebruikte ik figma dev om het scherm van de Apple Tv te maken voor de layout. Dat was handig want kon zo precies zien wat ik moest gebruiken voor de structuur.

![grid remote system](/images/readme/grid-system-remote.png)
![Opzetje van remote](/images/readme/opzetje-design-remote.png)
![remote trackpad](/images/readme/remote-trackpad.png)
![Figma dev styling](/images/readme/figma-dev-styling.png)
![Voorbeeld van het design opzetje](/images/readme/design-opzetje.png)
![Oude variant van het ontwerp](/images/readme/oude%20variant.png)

**Hoe lang duurde het?**
Duurde ongeveer 8 a 10 uurtjes

**Wat heb ik geleerd?**
Wat ik heb geleerd is om de stijling van de remote neer te zetten. Ik keek naar voorbeeld plaatjes van hoe het. moest en ging gewoon de voorbeelden aanhouden en daarvan de styling doen. Ik heb meer geleerd over de nesting en @layers, > & en. Ik weet nu beter hoe ik daar mee overweg moet

**Wat ga ik volgende week doen?**
Ik wil volgende week aan Syd of Sane vragen of aan iemand hoe je dan met de remote alles kan bediennen. Dat word mijn volgende stap tot interactie. En feedback vragen aan een docent of meer. Misschien ook beter uitbreiden qua concept. Want ik wil dat je door de apps kan navigeren met de remote Maar ik wil natuurlijk meer. Ook wil ik meer diepte in de remote zodat het er echt apple achtig uitziet.

#### Week reflectie

#### Feedback

Deze week had ik nog geen feedbackmoment. Ik was bezig met het concept uitwerken en de basis neerzetten. Dat kon ik zelf nog goed inschatten.

## week 2

### Week 2 18/05 - 22/05

**Wat heb ik gedaan?**
Deze week ben ik verder gegaan met de interactie van de remote. Na de feedback van Sanne ben ik overgestapt van checkboxes naar radio buttons zodat ik de :has()-selector kan gebruiken voor de navigatie. Ik heb de structuur van de HTML aangepast en de CSS opnieuw opgebouwd zodat de radio buttons de navigatie door de apps kunnen sturen. Ook ben ik bezig geweest met de styling van het Apple Tv scherm zelf, zodat de apps zichtbaar worden en je visueel kunt zien welke app geselecteerd is. De trackpad begint nu te werken als navigatie-element. Het kost nog wat moeite om alles goed op elkaar aan te laten sluiten maar het begint vorm te krijgen.

![Week 2 overzicht van de voortgang](/images/readme/uitleg-sanne.JPG)

**Hoe lang duurde het?**
Duurde ongeveer 8 a 10 uurtjes

**Wat heb ik geleerd?**
Ik heb geleerd hoe je radio buttons kunt gebruiken voor navigatie zonder JavaScript. De :has()-selector is heel krachtig en ik begrijp nu beter hoe je daarmee een geselecteerd element kunt stijlen vanuit een parent. Ook heb ik meer inzicht gekregen in hoe je CSS selectors combineert met de ~ en + om elementen te bereiken die na een geselecteerd radio button staan.

**Wat ga ik volgende week doen?**
Ik wil de navigatie verder uitbouwen zodat je echt door de app-lijst heen kunt scrollen met de remote. Ook wil ik de animaties en overgangen toevoegen zodat het meer op een echte Apple TV lijkt. Daarnaast wil ik de diepte van de remote verder uitwerken met meer detail en misschien een hover-effect toevoegen op de knoppen.

#### Week reflectie

Tweede week ging al beter dan de eerste. De overstap naar radio buttons was in het begin verwarrend maar nu snap ik waarom Sanne dat adviseerde. De :has()-selector opent echt veel mogelijkheden. Ik merk dat ik steeds handiger word met het nesten van CSS en het combineren van selectors. Het concept begint nu echt te leven.

#### Feedback Sanne

Sanne heeft mij deze week laten zien hoe ik de structuur van de remote moest aanpakken. Hij legde uit dat ik geen checkboxes moest gebruiken maar radio buttons, zodat je de `:has()`-selector kunt gebruiken om door de apps te navigeren. Hij liet ook zien hoe je de inputs bovenaan in de HTML plaatst zodat ze via `:has()` overal bereikbaar zijn. Op basis van deze feedback heb ik de hele HTML structuur omgebouwd en de navigatie opnieuw opgezet met radio buttons.

#### Bronnenlijst

- https://www.svgrepo.com

## week 3

### Week 3 25/05 - 31/05

**Wat heb ik gedaan?**
Deze week stond in het teken van finishing touches en het project verder uitwerken. Ik heb nieuwe apps toegevoegd aan de dock en een echte achtergrond afbeelding van Apple TV als achtergrond van het scherm gezet. Ook heb ik een profiel widget rechtsboven toegevoegd met de tijd en mijn memoji, net zoals op een echte Apple TV. Het glass effect van de dock heb ik verder verbeterd met `backdrop-filter`, `linear-gradient` en `inset box-shadow` zodat het er echt uitziet als glas. Daarnaast heb ik de code opgeschoond — overbodige inputs voor app-7, 8 en 9 weggehaald en de structuur leesbaarder gemaakt door de inputs in de `<li>` elementen te plaatsen bij hun bijbehorende app.
![Achtergrond van het Apple TV scherm](/images/readme/achtergronden.png)
![Memoji profielwidget toegevoegd](/images/readme/memoji.png)
![Zijkant van de remote klopte nog niet](/images/readme/zijkant%20niet%20nice.png)

**Hoe lang duurde het?**
Ongeveer 6 uurtjes

**Wat heb ik geleerd?**
Ik heb geleerd hoe je een realistisch glassmorphism effect maakt met alleen CSS. Het combineren van `backdrop-filter: blur()`, `brightness()`, `saturate()` en meerdere `box-shadow` waarden geeft een veel mooier resultaat dan een simpele transparante achtergrond. Ook heb ik geleerd hoe je code overzichtelijk houdt door inputs dicht bij hun bijbehorende elementen te plaatsen.

**Wat ga ik volgende week doen?**
Ik wil het openen van de muziek-app en Netflix werkend krijgen via de selecteer-knop op de remote. Ook wil ik dat de knoppen op de remote aanvoelen als echte knoppen met een klik-effect.

#### Week reflectie

Goede week. Het project begint er echt professioneel uit te zien. Het glassmorphism effect was een fijne ontdekking — door te experimenteren met de CSS waardes kon ik precies het effect krijgen dat ik wilde. Het opschonen van de code maakte het ook veel makkelijker om verder te werken.

#### Feedback Luna Jay

Luna Jay heeft naar mijn project gekeken en feedback gegeven over de visuele afwerking. Ze vond het concept sterk maar gaf aan dat het scherm er meer uit kon zien als een echte Apple TV — met een echte achtergrond, een profiel widget en een mooiere dock. Op basis van deze feedback heb ik de achtergrondafbeelding toegevoegd, het glassmorphism effect van de dock verbeterd en de profiel widget met memoji rechtsboven gezet.

## week 4

### Week 4 01/06 - 07/06

**Wat heb ik gedaan?**
Deze week heb ik de interactie verder uitgebouwd. Ik heb een box-shadow effect toegevoegd aan alle knoppen van de remote zodat je echt het gevoel krijgt dat je een knop indrukt — dit werkt puur met CSS via `:active` en `transform: scale()`. Daarnaast heb ik de muziek-app en Netflix werkend gemaakt via de selecteer-knop op de remote. Als je navigeert naar de muziek-app en op selecteer drukt, opent het Harry Styles scherm. Bij Netflix opent de intro video. Ook heb ik Arcade toegevoegd als derde openbare app. De power-knop werkt nu ook in twee richtingen — de CRT-uit animatie bij uitzetten en een CRT-aan animatie bij inzetten.

Daarnaast heb ik de responsive versie gebouwd. De grootste uitdaging was de remote — die ging in eerste instantie niet goed omdat de knoppen en trackpad vaste pixelwaardes hadden. De oplossing was om de remote op desktop al goed op te bouwen met de juiste verhoudingen, zodat ik hem op mobiel alleen hoef mee te schalen met `transform: scale()` en de losse elementen apart aanpas via de media query. Zo schaalt de hele remote inclusief knoppen proportioneel mee.

Tot slot heb ik een geanimeerde titel toegevoegd met een dancing shadow effect en een wavy beweging. De schaduwen wisselen tussen wit en Apple-blauw in alle richtingen, terwijl de tekst zachtjes op en neer beweegt.

![Remote was nog niet goed genoeg](/images/readme/remote%20niet%20goed%20.png)
![Responsive versie klopte nog niet](/images/readme/responsive%20niet%20goed%20genoeg.png)
![Proces van de responsive remote uitwerken](/images/readme/proces%20remote%20responsive.png)
![Puntjes op de i — eindresultaat](/images/readme/puntjes%20op%20de%20i.png)

**Hoe lang duurde het?**
Ongeveer 4 uurtjes

**Wat heb ik geleerd?**
Ik heb geleerd hoe je met radio buttons in combinatie met `:has()` meerdere onafhankelijke states kunt bijhouden. Door `name="scherm"` te gebruiken voor de app-schermen en `name="app"` voor de navigatie, werken de twee systemen los van elkaar. Ook heb ik geleerd hoe je met `:active` en `transform` een fysiek klik-gevoel simuleert zonder JavaScript.

Ik heb ook geleerd hoe belangrijk het is om de desktop versie goed op te bouwen voordat je responsive gaat werken — als de verhoudingen op desktop kloppen, is schalen op mobiel veel makkelijker. Verder heb ik ontdekt hoe handig de designer in de Google Chrome inspector is: je ziet letterlijk live wat je aanpast en hoe de stijlen op elkaar inwerken, zonder steeds de code te hoeven opslaan.

**Wat ga ik volgende week doen?**
Het project inleveren. Laatste puntjes op de i. Read me afschrijvne

#### Week reflectie

De beste week tot nu toe. De interactie voelt nu echt aan als een echte Apple TV remote. Het moment dat de muziek-app en Netflix openden via de remote was echt een goed gevoel. De combinatie van CSS-only navigatie met `:has()` en de animaties laat echt de kracht van CSS zien. De responsive versie was een uitdaging maar door goed na te denken over de opbouw van de remote is het uiteindelijk gelukt.

#### Feedback Choice

Choice heeft deze week naar het eindresultaat gekeken. Ze vond de CRT-animatie een leuk detail en het concept sterk. Ze gaf aan dat de apps ook echt openbaar moesten zijn via de selecteer-knop en niet alleen visueel geselecteerd. Daarnaast vond ze dat de remote nog niet goed genoeg was — de responsive versie klopte nog niet en de knoppen schaalden niet mee zoals het hoorde. Op basis van die feedback heb ik de muziek-app, Netflix en Arcade werkend gemaakt via de selecteer-knop, en ben ik verder gegaan met de responsive remote zodat alles correct meeschaftt op mobiel.

## Bronnenlijst

### Gebruikte tools & assets

- https://www.svgrepo.com — SVG iconen van de remote knoppen
- https://www.figma.com — Figma Dev voor de layout en structuur van het Apple TV scherm
- https://cssgrid-generator.netlify.app — CSS Grid generator voor de opbouw van de remote layout

### CSS technieken

- https://developer.mozilla.org/en-US/docs/Web/CSS/backdrop-filter — glassmorphism effect op de dock
- https://www.joshwcomeau.com/css/backdrop-filter/ — uitleg over next-level frosted glass met backdrop-filter
- https://css.glass — glassmorphism CSS generator, gebruikt als referentie voor het glass effect
- https://prismic.io/blog/css-text-animations — dancing shadow en wavy text animaties op de titel
- https://css-tricks.com/the-radio-state-machine/ — radio buttons als state machine, basis voor de CSS-only navigatie
- https://moderncss.dev/pure-css-custom-styled-radio-buttons/ — styling van radio buttons met pure CSS
- https://developer.mozilla.org/en-US/docs/Web/CSS/:has — uitleg over de :has() selector voor de app-navigatie

### Animaties & interactie

- https://codepen.io/francescostella/pen/ONaWvZ — TV turn-off animatie, inspiratie voor de CRT-uit animatie
- https://developer.mozilla.org/en-US/docs/Web/API/AudioContext — klik geluid via Web Audio API
