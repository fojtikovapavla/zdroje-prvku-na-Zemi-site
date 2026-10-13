# Zdroje prvků na Zemi — Blok 2 kurzu Chemické principy a udržitelnost

Slide decky a materiály k Bloku 2 (Management udržitelnosti, 1. ročník).
Stejný systém jako `chemie-ekosystemu-site` (Blok 1): statické HTML na
[reveal.js](https://revealjs.com/), sdílený vzhled v `assets/css/theme.css`,
nahrává se na GitHub Pages.

## Struktura

```
index.html             rozcestník Bloku 2
zadani-projektu.html   semestrální projekt „Ověř to v datech“ (8 témat, rubrika 20 b)
prednaska-1..6.html    přednášky 1–6
seminar-1..6.html      semináře 1–6
assets/css/theme.css   sdílený vzhled (z Bloku 1 + .slot-card, .owid-frame, .src-grid, .stat)
```

| # | Přednáška | Seminář | Prezentace projektu |
|---|---|---|---|
| 1 | Prvky na Zemi (původ, transmutace, složení, zdroje × zásoby, kritické suroviny) | Workshop Our World in Data, rozdělení témat | — |
| 2 | Li, C, Al, Si, Ge, In, Te | Koncentrace těžby × zpracování v datech | — |
| 3 | Fe, Ti, Cu, Co, Ni, PGM, vzácné zeminy | Elektromobily v datech, výpočty k oceli, toxicita kovů | T1, T2 |
| 4 | Sklo, cement, odpadní plyny, CO₂ (CCS/CCU) | Uhlíkový rozpočet, emise ČR výroba × spotřeba | T3, T4 |
| 5 | Petrochemie, polymery, recyklace, bioplasty | Recyklační kódy, osud plastů v datech | T5, T6 |
| 6 | Voda, strategie EU pro chemické látky, SSbD, PFAS | Vodní stres, hodnocení výrobku podle SSbD, závěr | T7, T8 |

Úroveň: chemie ze střední školy. Rovnice jsou jen tam, kde nesou pointu.
Podrobnosti a řešení úloh jsou v poznámkách pro přednášející (klávesa `S`).

## Data

Čísla v grafech jsou stažená z Our World in Data (stav 10/2026):
Minerals explorer (USGS/BGS, data za 2024), Global Carbon Project (CO₂ 2024),
OECD (plasty 2019), FAO AQUASTAT a WHO/UNICEF (voda), IEA (elektromobily).
Údaje z jiných zdrojů (IEA, ČHMÚ / Fakta o klimatu, odborné články) jsou
uvedené pod grafem nebo v poznámkách. Kde je hodnota jen řádový odhad,
poznámka to říká a doporučuje ji před přednáškou ověřit.

Semináře obsahují živé grafy OWID (`<iframe data-src=…>`). Potřebují
internet, pod každým je odkaz pro otevření v nové záložce.

## Ovládání

Šipky / mezerník = další snímek, `F` = celá obrazovka, `S` = poznámky.
Kvízy: kliknutím na možnost se ukáže odpověď. Karty se otáčejí kliknutím.

## Nahrání na GitHub Pages

Nové repo, nahrát obsah složky, Settings → Pages → větev `main`, `/ (root)`.
