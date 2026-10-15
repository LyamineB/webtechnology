# Labo 2 - reflecties

Naam: Lyamine Boudoudouh

## 2. Selectors lezen

Welke elementen raakt elke selector? Eén zin per selector.

- a. `header nav ul li a`: Al de links in de nav bovenaan.
- b. `article > p`: De vier p's die rechtstreeks (>= direct kind v (v L --> R)) in article staan.
- c. `.uren li:nth-child(3)`: Derde li in ul uren. 
- d. `h2 ~ p`: Kiest 4p's  rechtstreeks uit article .(~= elke .. na .., binnen dezelfde ouder)
- e. `.rassen li:first-child`: (.rassen li= de spatie betekent afstammeling, dus elke li binnen in rassen, ook diep binnenin) (:first-child= eerste kind van zijn eigen ouder, dus elke eerste li vn de 3ul's) DUS drie elementen: honden, herders en herderkruisingen, en Europese korthaar

## 3. Voorspel, dan kijk

Vul de eerste twee kolommen in vóór je de pagina opent. Trede: herkomst, specificiteit, volgorde of overerving (of iets anders, benoem het).

| vraag | mijn voorspelling (kleur) | beslissende trede | uitkomst in de browser | juist? |
|---|---|---|---|---|
| 1 | green | herkomst | | |
| 2 | blue | volgorde | | |
| 3 | red |specificiteit | | |
| 4 | green | selector raakt niet | red | `.v4 > a` raakt niets: de `a` is geen direct kind van de section; alleen `.v4 a` raakt |
| 5 | blue| specificiteit | | |
| 6 | blue| overerving verliest | |  `.v6-tekst` raakt de `p` zelf; de rode kleur op de section is alleen geërfd |
| 7 | red| overerving | | geen enkele regel raakt `blockquote`; hij erft van `.v7`|
| 8 | blue | inline-style | |  het style-attribuut wint van elke selector in de stylesheet (2.3) |
| 9 | red | specificiteit (important)| | |
| 10 | green | volgorde | vergeten puntkomma (F2.3) | `font-size: 1.5rem color: blue` is één onbegrijpelijke declaratie; de browser laat ze vallen en `color: green` blijft | |

Bij welke vraag zat je fout, en wat was de reden? (Alles juist? Welke vraag duurde het langst, en waarom?)

## 4. De nabouw

- Welke selector koos je voor de links in de navigatie, en waarom geen class?
- Welke regel kostte je het meeste tijd, en wat was uiteindelijk de oorzaak?

## 6. Je site

- Welke drie waarden staan in je tokenblok, en waarom die?
- Wat verandert er in je site als je één token wijzigt?

## Thuis: R2.3 (met AI)

Prompt en onbewerkte output staan in `review/`. Minstens vijf bevindingen, elk met een verwijzing naar de sectie of het foutnummer:

1. 
2. 
3. 
4. 
5. 
