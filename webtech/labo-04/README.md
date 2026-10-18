# Labo 4 - reflecties

Naam: (Majd Makdesi)

## 1. Drie kolommen

- Op welk element staat `display: flex`, en op welke elementen staat `flex`?display: flex staat op de container (het bovenliggende element). flex staat op de drie kolommen zelf.
- Waarom staan die twee niet op hetzelfde element? Omdat display: flex de indeling regelt en flex bepaalt hoeveel ruimte elke kolom krijgt.

## 2. Navigatiebalk

- Welke property verdeelt de ruimte langs de hoofdas, en welke lijnt uit op de kruisas? justify-content verdeelt de ruimte langs de hoofdas en align-items lijnt de elementen uit op de kruisas.
- Wat gebeurt er met de links als je `gap` vervangt door `margin-right` op elke `li`? De links krijgen ook ruimte tussen elkaar, maar de laatste link krijgt rechts extra ruimte. Bij gap is er alleen ruimte tussen de links.

## 3. Mondriaan

- Welke twee vlakken moest je expliciet plaatsen, en waarom volstond de impliciete vulling voor de andere vier?De twee vlakken die een speciale plaats moesten krijgen. De andere vier werden automatisch door Grid geplaatst in de vrije vakken.
- Waarom is `gap` hier beter dan een border op elk vlak? Omdat gap zorgt voor gelijke ruimte tussen de vlakken. Met border krijgt elk vlak een eigen rand.

## 4. Trap

- Wat zie je als je de `grid-row`-declaraties weghaalt, en waarom? De treden staan dan niet meer op de juiste plaats, omdat Grid ze automatisch in de vrije vakken zet.
- Wat betekent `grid-column: 4 / -1` voor de laatste trede, en waarom werkt het hier ook? De laatste trede begint bij gridlijn 4 en loopt tot de laatste gridlijn. Dit werkt omdat Grid die lijnen gebruikt om de trede te plaatsen.

## 5. Dierenasiel Zonnehoek

- Hoeveel layoutcontainers telt deze pagina, en welk gereedschap koos je voor elk?Er zijn 3 belangrijke layoutcontainers. Ik gebruikte Flexbox voor de navigatiebalk en de pagina-indeling, en Grid voor de kaarten met dieren.
- Verklein het venster tot de helft: wat breekt er, en in welk hoofdstuk wordt dat opgelost? De kaarten worden te smal en de tekst past niet meer goed. Dit wordt opgelost bij responsive design, met media queries.

## Thuis: B4.1 (met AI of zonder AI)

Welke route koos je? Bij de AI-route: prompt en onbewerkte output staan in `site/review/`, en dit corrigeerde ik (met verwijzing naar de sectie of het foutnummer):

1. 
2. 
3. 
