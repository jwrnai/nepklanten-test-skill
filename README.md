# nepklanten-test

Een skill voor Claude die je bedrijfsidee test op honderd nepklanten, voordat je er geld in steekt.

## Wat het doet
Claude verzint honderd verschillende kopers, elk met een eigen budget, eigen gewoontes en een eigen reden om nee te zeggen. Daarna pitcht hij je idee aan ieder van hen en zie je in een tabel wie kocht, wie twijfelde en wie afhaakte en waarom. Met deze skill:

1. vraagt Claude kort naar je idee, je prijs, waar de koper het tegenkomt en voor welk land;
2. maakt hij 100 kopers in 4 tot 6 echte groepen, ook mensen die het nu met iets anders oplossen;
3. pitcht hij je idee aan elke koper en laat ieder in eigen woorden kopen, twijfelen of afhaken;
4. zet hij alles in één tabel met de telling per groep;
5. geeft hij de top 5 redenen om af te haken, wat je kunt aanpassen en drie vragen om bij echte klanten te checken.

Het is een simulatie, geen marktonderzoek: gebruik het om bezwaren te vinden, niet om je omzet te voorspellen.

## Installeren in 3 stappen
1. Download of clone deze map.
2. Zet de map `nepklanten-test` in `~/.claude/skills/` (of plak in Claude Code: "Maak hier de skill nepklanten-test van.").
3. Typ in Claude Code `/nepklanten-test` en beschrijf je idee, bijvoorbeeld "een online cursus videobewerken voor ondernemers".

Werk je in de Claude desktop app zonder skills? Plak dan de inhoud van `nepklanten-test/SKILL.md` als eerste bericht en zet je idee eronder.

## Wat erin zit
- `nepklanten-test/SKILL.md`: de skill zelf.
  - Wat Claude eerst vraagt.
  - Honderd kopers met budget, gewoontes en een reden om nee te zeggen.
  - Dezelfde pitch voor iedereen, met koopt, twijfelt of haakt af.
  - De tabel, de top 5 afhaakredenen en wat je kunt veranderen.
  - Drie vragen voor echte klanten.

## Waar het op leunt
- Rob Fitzpatrick, *The Mom Test*: vraag naar gedrag, niet naar meningen.
- Clayton Christensen, *Competing Against Luck*: jobs to be done.
- Alberto Savoia, *The Right It*: eerst goedkoop testen, dan bouwen.
- Argyle e.a. (2023), *Out of One, Many*: taalmodellen als nagebootste groepen mensen, met hun beperkingen.
- Onze eigen regels: kort, Nederlands, alleen echte getallen.

Licentie: MIT.
