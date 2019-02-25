# ToDone
Deze oefening moet je begeleid maken tussen de labo-lessen:
- Werken met HTML & CSS op een correcte manier.
- CSS herhalen; variabelen, CSS-grid, ITCSS schrijven.
- JS op een correcte en nette manier te schrijven.


- Oefenen van het constructor en  het module pattern.
- Opzetten van een taskrunner:
	- Opzetten van browsersync.
	- Gebruik van SASS in combinatie met ITCSS.
	- Optimalisatie van browser parsing en rendering.

## Layout
Je bent vrij om de layout aan te passen en kleuren of fonts zelf te kiezen.
De opgave heeft een themakleur, in het voorbeeld is dit 'OrangeRed'. De gutter is meestal 24px of eventueel een ander veelvoud van 8px. Als font wordt [Muli](https://fonts.google.com/specimen/Muli) gebruikt.

- [ ] Je kan todo's toevoegen en weer afvinken.
- [ ] Voorlopig laten we een todo die we afvinken uitfaden en verwijderen we dit uit de DOM. Hou dit voorlopig wel nog bij in de localStorage.
- [ ] Bij het toevoegen van een item hebben we aantal categoriën om te categoriseren.
- [ ] Vermijd de mogelijkheid om een lege Todo toe te voegen.

## HTML
We gebruiken zoveel mogelijk de correcte semantische tags.
Denk aan; section, article, nav, aside, main, etc...

## CSS
De layout van de checkbox is met CSS.
Wat doe je met een checkbox die weg gaat? Denk aan de werking van de notifications in het vorige labo.

## Script
Voorzie voor deze oefening de volgende bestanden:
- ```app.js``` Hiermee _starten_ we de app. Met een self-evocing function gaan we de data ophalen en vervolgens de todo's die we beschikbaar hebben weergeven.
- ```/lib/dataAccess.js``` Een zo generiek mogelijke manier om Todo's via crud bij te houden in localStorage. (We willen hier later onze eigen API aan hangen, dus we gaan functie-namen kiezen die we ook voor een API handig zouden vinden...)
- ```/lib/todo.js``` Dit wordt een constructor pattern waarin we telkens een nieuwe todo kunnen aanmaken. Bedenk welke properties er nodig zijn en hoe je dit zo performant mogelijk kan doen. Je kunt dit ook doen met een ES6 class.
- ```/lib/todoModule.js``` Hier gaan we todo's ophalen, bijhouden, enz... Ook de interacties met de DOM kunnen we hier doen (dit kan je ook opsplitsen naar ```/lib/bindUI.js``` of iets dergelijks).

Voorbeeld van de layout:
![ToDone oefening](https://i.imgur.com/aln2FEY.png)

## Uitbreiding:
- Hoe zou je SEO kunnen verbeteren op deze pagina(s)? Bespreek dit tijdens de les.
- Maak de naam (Hello __Naam__) aanpasbaar en sla dit op in localStorage. Tip: bekijk het _contenteditable_ attribuut.
- Maak de website so goed mogelijk responsive:
	- Zijn de knoppen groot genoeg om op te klikken?
