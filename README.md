# Examinationsuppgift **Datalogiskt tänkande**

[Här är URL:en](https://www.figma.com/file/ZjVJX9hQPDmKqxeyKSxM6u/Examinationsuppgift---Datalogiskt-t%C3%A4nkande?type=whiteboard&node-id=0%3A1&t=pJwPZjhfoYT8H2af-1)

## Inledning
Vi valde att planera ut hur vår tid skulle användas, själva projektets process gick vi inte igenom utan började tillsammans och fundera ut uppgiften.

Under tiden vi skrivit och spånat så har vi suttit i Discord och konverserat.

## Decomposition
Vi följde instruktionerna som vi fått, bryta ner sidan i mindre och mindre sektioner.

Vi vet inte om man ska göra det på något annat sätt, men det blev enklare och tydligare att se vart saker är i en trädstruktur.

## Pattern Recognition
Vi började jämföra vad som är lika varandra, använde färgkoder för att enkelt se hur många olika "delar" hemsidan bestod av.

Började med fler uppdelningar, men märkte senare att olika saker hade fler gemensamma nämnare än vi trodde.

## Abstraction
Svårt koncept att greppa, men vi började få förståelse mer för vad det betyder. När man började tänka på det så blev det väldigt tydligt hur man kan slå ihop fler saker till mer universella funktioner. Vi började med 3 olika slags knappar (En för pop up delar, en annan för addera till kaffelistan och en tredje till att förflytta sig mellan sidor), men då alla hade specifika delar som man kunde återanvända så kunde vi koka ner det till en "button".


## Algorithm Design
Man kunde ha gått väldigt djupt, men med tanke på att vi skulle följa det flödet vi fick som uppdrag så valde vi att göra det lite simplare. 

Stegen är indelade per "sida" och vad som sker på respektive sida.


## Våra tankar

Abstraktions biten var svår att hänga med på, blir lätt ett luddigt tema, men resten var enklare. När man väl kom in i uppgiften så gick det lite enklare. 

### Egna tolkningar: 
- ***Index* sidans funktionalitet**

    Det var svårt att se hur sidan skulle gå från Index till t.ex /menu, eller om man skulle hamna på profildelen. Vi drog slutsatsen att "sidan" visas medan data hämtas i bakgrunden för att göra det enklare när väl sidan är igång.
- ***Status* sidans funktionalitet**

    Några tankar vi hade om Status sidan är om den skulle fungera som en **"Pop up"**, likt NAV-menyn eller varukorgen. Vi valde det, och lät knappen att "toggla" sig ur vara **"Ok, cool!"** knappen. 
    Sen var en till fundering gällande var man skulle hamna efter den rutan. Men sen såg vi att **"Orderstatus"** fliken fanns med i NAV-menyn, så då valde vi att man återgår till den, med **/menu** bakom 
