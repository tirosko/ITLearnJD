# ITLearnJD

Pracovný priestor pre vytváranie spoločných programovacích zručnosti pre učenie JD.

Tento návod popisuje, ako spolu pracujeme.

## Ako to funguje (v skratke)

1. Vlastník vytvorí **Issue** s úlohou.
2. Ty si úlohu vezmeš (priradíš sa) a vytvoríš si **vetvu**.
3. Spravíš zmeny a **commitneš** ich.
4. Otvoríš **Pull Request** (PR) a vyplníš šablónu.
5. Vlastník PR skontroluje, prípadne napíše pripomienky, a potom ho schváli.

## Krok za krokom

### 1. Vyber si úlohu
Otvor záložku **Issues** a vyber úlohu, ktorú ti niekto zadal. Prečítaj si popis a kritériá prijatia. Ak je niečo nejasné, napíš komentár.

### 2. Vytvor vetvu
Názov: `issue-<číslo>-krátky-popis`, napr. `issue-12-uvodna-stranka`.

```bash
git checkout main
git pull
git checkout -b issue-12-uvodna-stranka
```

### 3. Pracuj a commituj

```bash
git add .
git commit -m "Pridaná úvodná stránka (Refs #12)"
git push -u origin issue-12-uvodna-stranka
```

### 4. Otvor Pull Request
Na GitHube klikni na **Compare & pull request**. Šablóna sa vyplní sama, doplň všetky body. V popise uveď `Refs #12`.

### 5. Reaguj na pripomienky
Ak vlastník napíše pripomienky, oprav ich v tej istej vetve a pushni. PR sa aktualizuje automaticky.

## Hlásenie problémov
Ak niečo nefunguje, vytvor Issue so šablónou **Bug / problém** a popíš, ako sa chyba dá zopakovať.

## Dôležité pravidlá

- Do `main` nepíšeme priamo, len cez Pull Request.
- Do repozitára nikdy nevkladáme heslá, tokeny ani osobné údaje.
- Jedna úloha = jedna vetva = jeden PR.
- Podrobné pravidlá pre prácu s AI sú v [AGENTS.md](AGENTS.md).

## Štruktúra repozitára

```
AGENTS.md                          pravidlá pre Kubka a AI
README.md                          tento návod
Teoria/  Zadania/  Riesenia/  PracovnyPriestor/
.github/ISSUE_TEMPLATE/            šablóny úloh a problémov
.github/PULL_REQUEST_TEMPLATE.md   šablóna odovzdania
```
