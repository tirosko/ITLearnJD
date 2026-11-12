# ITLearnJD – pravidlá pre Kubka a AI asistentov

Tento súbor čítaj pred každou prácou na projekte (človek aj AI).

## Cieľ projektu

ITLearnJD je spoločný projekt na učenie IT. Dôraz je na zrozumiteľnosť, malé kroky a to, aby autor rozumel každej zmene.

## Pracovný postup

1. Každá úloha má svoj **Issue** (šablóna `task-feature` alebo `bug-problem`). Najprv prečítaj zadanie.
2. Pre každú úlohu vytvor **samostatnú vetvu**: `kubko/issue-<číslo>-kratky-popis` (napr. `kubko/issue-12-uvodna-stranka`).
3. Pracuj v **malých krokoch** a commituj často. Správa commitu je stručná a výstižná, na konci `Refs #<číslo>`.
4. Hotovú prácu odovzdaj cez **Pull Request** podľa šablóny. Do `main` sa nepíše priamo.
5. `main` sa mení len po schválení vlastníka repozitára. Issue zatvára vlastník, nie autor PR.

## Pravidlá pre AI asistentov

- Najprv prečítaj Issue a existujúce súbory, až potom navrhuj zmeny.
- Rob len to, čo zadanie vyžaduje. Žiadne nesúvisiace refaktoringy, premenovania ani presuny súborov.
- Dodrž štýl a konvencie okolitého obsahu.
- Vysvetli, čo a prečo si zmenil, jednoducho a po slovensky.
- Nikdy nevkladaj do repozitára heslá, tokeny, API kľúče ani osobné údaje.
- Nevymýšľaj si: ak niečo nevieš alebo si to neoveril, napíš to otvorene.
- Netvrď, že si niečo otestoval, ak si to nespustil.
- Pri nejasnom zadaní sa najprv opýtaj.

## Pravidlá pre Kubka

- Ak niečomu nerozumieš, napíš komentár do Issue. Pýtať sa je v poriadku.
- Pred odovzdaním si svoju zmenu ešte raz prečítaj a prejdi kontrolný zoznam v PR.
- Jedna úloha = jedna vetva = jeden Pull Request.

## Definícia hotovej úlohy

- Splnené všetky body z Issue (kritériá prijatia).
- Zmena je overená (spustená / otvorená / prečítaná) a v PR je napísané ako.
- Žiadne nesúvisiace zmeny a žiadne citlivé údaje.
- Ak sa zmenilo správanie alebo postup, upravený je aj `README.md`.
