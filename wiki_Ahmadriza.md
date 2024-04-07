# Proces verslag


# Week 3

Deze week ben ik bezig geweest met het onderwerp “formulieren” en de opdrachten ervan gemaakt . En daarnaast heb ik ook de verdieping stof bestudeert en deels gemaakt van het animeren in de frontend. Ik heb geleerd hoe je met de data api contact kunt maken en een GET request en POST request kunt doen. Hierbij was het belangrijk om eerst goed de JSON bestand te bestuderen omdat je dan makkelijk de data kunt opvragen die je zou willen.

Om de data op te slaan en in ons geval de data voor het aanmaken van de gebruiker moest je een POST request doen via de API. Wij hadden al code gemaakt met html en css voor het formulier dus het enige wat er bij moest was de JS. En in de JS geef je aan welke elementen gemanipuleerd moet worden in een functie, vervolgens maak je een object met de gebruikersgegevens bijv. Username, password etc, vervolgens maak je een Fetch request naar de API met de POST methode en hier maak je ook weer gebruik van de .then en .catch, en als laatst voeg je een event listener toe aan het formulier om de functie uit te voeren wanneer er op de knop word geklikt.

**Leermomenten:**

* Goed kijken naar het JSON bestand om zo de juiste data aan te spreken
* In de API als je een POST request stuurt de code in de juiste formaat te schrijven
* .then en .catch gebruiken bij een foutmelding of als het succesvol is gegaan


# Week 4
### Oriënteren en begrijpen: 
Deze week ben ik alvast bezig geweest met het bouwen van mijn future. Ik was bezig met het filter gedeelte. Hiervoor had ik eerst uitgezocht wat voor filters er allemaal zijn en welke filters handig zijn voor mijn future.

### Verbeelden en conceptualiseren: 
De volgende stap was om een eerste schets te maken hoe ik de filter wil hebben qua lay-out en structuur dus hiervoor had ik in XD een schets gemaakt.

<img width="150" alt="Scherm­afbeelding 2024-04-06 om 16 24 17" src="https://github.com/Tbjamie/project-tech-group/assets/150698950/7ad5194f-ce3a-49df-8d49-6e815ff41946">



### Prototypen en uitwerken: 
 Als eerst ben ik begonnen met basic html en css te schrijven. Denk hierbij aan: Sections, Articles, H1, H2.., P, Buttons etc. Daarna had ik voor mijn filter een range slider gemaakt voor de leeftijd categorie en buttons voor de genres. 


### Evalueren: 
Na het maken van mijn 1e versie vroeg ik feedback aan een van mijn teamgenoten. Uit het feedback kwam naar voren dat het beter is om de leeftijdscategorie met buttons te maken en de taal en genres met een dropdown te maken omdat we in de API veel genres en landen hebben.

Wat is allemaal gelukt deze week:
* 1e versie te maken van mijn future
* Onderzoek gedaan naar de mogelijkheden voor het filteren
* Feedback gevraagd en deels al verwerkt



# Week 5
### Oriënteren en begrijpen: 
Deze week was ik bezig om de data op te halen van het json bestand en toe te passen in mijn filters (genre en taal). Hiervoor ging ik eerst het json bestand bestuderen en kijken welke data ik nodig heb en hoe deze gestructureerd was zodat ik het later juist kon aanroepen in mijn JS.

### Verbeelden en conceptualiseren:
Nu ik de data goed had bestudeerd kon ik in XD een schets maken hoe ik de structuur en lay-out eruit wil laten zien. 

<img width="150" alt="Scherm­afbeelding 2024-04-06 om 16 22 36" src="https://github.com/Tbjamie/project-tech-group/assets/150698950/5d217b6b-9c36-4426-973a-b6e2f2ae24ca">



### Prototypen en uitwerken: 
Na ik het bestand goed bestudeerd had en een eerste schets had gemaakt kon ik nu in mijn JS file de code schrijven. Eerst had ik een fetch functie aangemaakt die connectie maakt met de json bestand. Daarna de code geschreven dat ik de genres in mijn dropdown wil hebben. Vervolgens had ik de dropdown gemanipuleerd en daar een VAR van gemaakt om deze later aan te roepen. Nu ik een stukje verder was gekomen met het schrijven van de code liep ik ergens tegen aan namelijk: de data was zichtbaar maar het was niet in mijn dropdown dus iets was in de code niet goed gegaan. Na een paar keer proberen om het probleem zelf op te lossen vroeg ik een van mijn teamgenoten om hulp en hij legde mij uit wat ik verkeerd had gedaan namelijk: dat ik in mijn html de articles niet hoeft te maken en ik het kan aanmaken in mijn JS, verder had ik een createElement moeten maken voor de "option" om het in de dropdown te laten zien.


### Evalueren:
Nu ik al een eindje verder was ging ik tussendoor aan een van mijn teamgenoten vragen om feedback. Uit het feedback kwam naar voren dat ik voor de taal een API kan zoeken of ook een JSON bestand zodat ik het op hetzelfde manier kan gebruiken als de genre JSON bestand.


# Week 6
### Oriënteren en begrijpen: 
Deze week was ik bezig om de data van de gefilterde users alvast een lay-out te geven en het te laten zien met JS via fetch. Hiervoor had ik eerst naar verschillende voorbeelden gekeken hoe andere soortgelijke apps/sites het doen zodat ik inspiratie had gekregen en vanuit daar verder kon gaan.

### Verbeelden en conceptualiseren:
Nu ik de data goed had bestudeerd kon ik in XD een schets maken hoe ik de structuur en lay-out eruit wil laten zien. 

<img width="150" alt="Scherm­afbeelding 2024-04-06 om 16 19 14" src="https://github.com/Tbjamie/project-tech-group/assets/150698950/31a0cf46-b3cc-4e3f-b92f-b5947b5d74dd">

### Prototypen en uitwerken: 
Na ik een schets had gemaakt kon ik het nu coderen. Eerst was ik begonnen met het maken van een test JSON bestand met een paar elementen omdat de database nog niet klaar was. Vervolgens had ik met fetch voor de 3e section (aanbevolen users) code geschreven. Hier had ik een VAR gemaakt die verwijst naar de Article en een VAR username die word aangemaakt in de h3. Vervolgens een VAR voor de username.innerText die pakt het element van het JSON bestand die ik had gemaakt en laat het weergeven in de html. vervolgens deze code geschreven     matchSection.append(userArticle) userArticle.append(username) dat het word weergeven in de juiste section die ik eerder had aangemaakt in een VAR. vervolgens heb ik 2x bij een "P" hetzelfde gedaan dus de data van het JSON bestand gehaald. Bij 1 "P" en 1 button heb ik een innerText gebruikt om eigen tekst ook naar voren te brengen bijv. voor de button een "Add friend" tekst.

### Evalueren:
Nu ik al een eindje verder was ging ik tussendoor aan een van mijn teamgenoten vragen om feedback. Uit het feedback kwam naar voren dat ik de structuur en lay-out kon aanpassen met JS en CSS. Dus de User naam boven vervolgens daaronder "Match based on" en dan de gekozen filters zodat de gebruiker ook een overzicht heeft wat hij had gekozen.


# Week 7
### Oriënteren en begrijpen: 
Omdat we nog geen echte future hadden van het matchen van de users, hadden we besproken dat ik dat ging ontwikkelen. Omdat deze future meer relevant was voor onze app had ik mijn andere future (gefilterde users) gelaten. Om een concept te bedenken ging ik eerst inspiratie opdoen op het internet om zo tot ideeën te komen.

### Verbeelden en conceptualiseren:
Nu ik de data goed had bestudeerd kon ik in XD een schets maken hoe ik de structuur en lay-out eruit wil laten zien. 

<img width="550" alt="Scherm­afbeelding 2024-04-06 om 16 25 31" src="https://github.com/Tbjamie/project-tech-group/assets/150698950/798a3d60-4e6c-4a40-9aef-83a9407376f8">


### Prototypen en uitwerken: 
Na ik een schets had gemaakt kon ik het nu coderen. Eerst was ik begonnen met het maken met basic html en css te schrijven voor de genre, taal, faro game en antwoorden pagina. Denk hierbij aan: Sections, Articles, H1, H2.., P, Buttons etc. Omdat ik voor mijn vorige future al een dropdown had gemaakt voor de genre en taal met de fetch functie kon ik dat gewoon kopiëren en alleen aanpassen in de een ander stijl d.m.v. css. Ook had ik toegevoegd dat als je een genre of taal heb gekozen dat het dan tevoorschijn komt op een button zodat je die ook weer kunt deslecteren dit had ik gedaan omdat het dan ook consistent twas met de discover pagina.

Voor de Fafo games pagina had ik een search future gemaakt waarbij je een game kunt intypen die word opgehaald van de database. Ik heb er ook voor gezorgd dat alle games niet zichtbaar zijn in het begin met display none. Alleen als je een stukje van het woord type dat er dan al resultaten komen. Ook heb ik toegevoegd dat als je een game heb opgericht dat je het later kan zien in de searchbar wat je allemaal had opgezocht.


### Evalueren:
Nu ik al een eindje verder was ging ik tussendoor aan een van mijn teamgenoten vragen om feedback. Uit het feedback kwam naar voren dat ik voor de genre en taal pagina de de selecteer functie kan weg laten anders staat het er dubbel op en dat kan voor de gebruiker verwarring veroorzaken. Maar wel kon het op de antwoorden pagina dat je daar jouw antwoorden kunt inzien en kunt aanpassen.

En omdat ik nu alles in losse html pagina's had was de feedback om het in een html pagina te maken en het aan te roepen met JS via de DOM.


# Week 8
Deze week had ik de questions van de match app die in losse html pagina's waren toegevoegd in 1 gehele html pagina. Dit had ik samen gedaan met de hulp van Keysha.
 

### Prototypen en uitwerken: 
Als eerst hadden we alle code van de body van elke html pagina in 1 pagina gecombineerd met per pagina 1 section. Nu was alles wel op 1 pagina maar uiteindelijk moesten we ervoor zorgen dat er steeds 1 pagina per keer in beeld kwam. Hiervoor hebben we onderzoek gedaan en kwamen erachter dat je en form kunt gaan gebruiken met verschillende "fieldset". Dus per pagina hadden we in een fieldset gezet met daarin een "legend" waarmee we de vraag van de pagina mee gingen benoemen en de "input" en hier kwam dan de dropdown voor genre en taal, searchbar voor favo game en de radio buttons voor de verschillende platformen. Nu we alle pagina's in een aparte fieldset hadden gezet hadden we de alle fieldset een "id" gegeven om dat in JS aan te roepen dat er steeds 1 pagina per keer verschijnt en de andere op display none wordt gezet. hiervoor hadden we een event listener toegevoegd op de next en previous button dat wanneer je op de button klik je naar de volgende of vorige pagina gaat en dat er steeds 1 pagina per keer verschijnt.


Als eerst hadden we de answers pagina niet in een fieldset gezet maar in een section maar later in de browser zagen we dat wanneer je op de button klik je wel steeds naar een andere pagina gaat maar dat de answers pagina steeds in beeld was dus uiteindelijk hadden we de answers pagina ook in een fieldset gezet en ook een aparte "id" gegeven zodat we dat konden aanroepen in de JS.

Daarnaast had ik ook toegevoegd dat alle vragen van de quiz worden opgeslagen en worden getoond in de antwoorden pagina in de h3. Zo kan de gebruiker makkelijk een overzicht hebben van zijn antwoorden. En als laatste had ik ervoor gezorgd dat je jouw antwoord ook kon wijzigen d.m.v. op de edit button te klikken. Hier heb ik een eventlistener toegevoegd aan de button en wanneer je bijv. op vraag 1,2 of 3 klikt dat je dan een dropdown krijgt met de genre, taal en platform die je dan kunt aanpassen en bij vraag 4 een searchbar om jouw fafo game aan te passen. 

Hiervoor heb ik de fetch functie gekopieerd en aangepast dat het in de antwoorden pagina word aangeroepen en niet in de taal of genre pagina. En voor de platform heb ik een eigen dropdown gemaakt met alle platformen erin. En alle edit functies zitten op een display none en worden pas geactiveerd wanneer je op een van de edit buttons klikt. En wanneer je bijv. een antwoord heb gewijzigd dan komt het nieuwe antwoord in de h3 te staan van de antwoord pagina.


### Evalueren:
De feedback dat we kregen is dat je inplaats van sections een form kunt gaan gebruiken met verschillende fieldset en een input zodat je dat makkelijk kunt aanroepen in JS.


