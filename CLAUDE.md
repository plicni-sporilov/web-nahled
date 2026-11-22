## Znalostní báze

Rozcestník napříč projekty je v Notionu: stránka "🧭 Znalostní báze",
ID 3cbbc4257130811b8e7ae7a0b597713e, sekce Private.
Obsahuje databázi Projekty — jedna stránka na projekt,
data source `collection://a3ee2721-e60c-4f3f-805b-248a75c67ab3`.
Udržuje ji skill `predej`. Stejná báze je sdílená s webovým chatem Claude.

Než začneš pracovat na provozním, technickém nebo projektovém úkolu,
a pokud jsi tak v této session ještě neučinil, načti tuto stránku
a z databáze Projekty stránku odpovídajícího projektu.
U krátkých faktických otázek to nedělej.
Není-li Notion konektor dostupný, vystač si s `docs/STAV.md` a zmiň to.

Technická dokumentace bydlí u kódu, ne v Notionu — odsud se na ni jen odkazuje.
Rozhodnutí naopak zůstávají v Notionu v plném znění: je to jediná vrstva,
na kterou dosáhne každé prostředí bez dalšího kroku; repozitář vidí jen
session, která ho má připojený.

## Tento repozitář

- Stav práce a otevřené body: `docs/STAV.md`
- Stránky webu: `*.html` v kořeni, fotky v `img/`; přehled v `README.md`
- Zadání pro webmastera je Claude Doc „Web plicnisporilov.cz – zadání úprav“ (odkaz na stránce projektu v Notionu); při změně obsahu náhledu zkontroluj, jestli se nemá změnit i zadání

**Repozitář je veřejný kvůli GitHub Pages (výslovné rozhodnutí uživatele) — nikdy sem nepatří data pacientů, interní dokumenty ani přihlašovací údaje, a každá stránka musí mít `<meta name="robots" content="noindex, nofollow">`.**

## Kam co patří

- cizí zdrojový materiál (fotky v plném rozlišení, logo ve vektoru, propagační video) → Google Disk,
  vlastnost `Podklady` na stránce projektu; do gitu nepatří, verzujeme jen to,
  co píšeme sami (do `img/` jen zmenšené fotky pro web)
- poznatek o systému, destilát → příslušný dokument v repozitáři `handoff`, ne sem
  (u tohoto projektu zatím žádný)
- stav práce na tomhle projektu → `docs/STAV.md`
- rozhodnutí a orientace → Notion, stránka projektu
