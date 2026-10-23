# AI hry

Web **aihry.roud.cz**: katalog výukových her pro děti, které vznikají s pomocí umělé inteligence. Všechno je statické HTML, bez buildu a bez serveru.

```
index.html               katalog her (filtry podle kategorií a štítků)
proc-hrat/index.html     článek: proč AI hry a proč ne plošný zákaz mobilů
assets/site.css          vzhled katalogu a článku
assets/games.js          seznam her (název, popis, věk, kategorie, štítky)
hry/<slug>/index.html    jednotlivé hry, každá je samostatný soubor
```

## Jak přidat hru

1. Ulož hru jako `hry/<slug>/index.html`. Má fungovat i samostatně, otevřená dvojklikem.
2. Připiš záznam do `assets/games.js`. Kategorie a štítky se ve filtrech objeví samy.

## Hry

- **Zvířátková škola** (`hry/zviratkova-skola/`): podstatná a přídavná jména, třídění slov a anglická slovíčka se zvířátky. Zadání čte nahlas, vysvětluje odpovědi a obtížnost roste postupně (2 → 3 → 4 možnosti). Slova jsou na začátku skriptu (`ANIMALS`, `TRAITS`, `NOUNS`, `ADJECTIVES`).

## Nasazení

Web patří na server `app` (app.roud.cz, 185.216.203.188) jako statický web pro doménu `aihry.roud.cz`. DNS (A a AAAA záznam na `app`) je nastavené. Stačí obsah repozitáře nakopírovat do složky webu a v proxy na serveru přidat doménu `aihry.roud.cz`, která ji servíruje.

Autor: [Tomáš Roud](https://roud.cz/)
