# AI hry

Web **aihry.roud.cz**: katalog výukových her pro děti, které vznikají s pomocí umělé inteligence. Všechno je statické HTML, bez buildu a bez serveru.

```
index.html               katalog her (filtry podle kategorií a štítků)
proc-hrat/index.html     článek: proč AI hry a proč ne plošný zákaz mobilů
assets/site.css          vzhled katalogu a článku
assets/games.js          seznam her (název, popis, věk, kategorie, štítky)
hry/<slug>/index.html    jednotlivé hry, každá je samostatný soubor
CNAME                    doména pro GitHub Pages
```

## Jak přidat hru

1. Ulož hru jako `hry/<slug>/index.html`. Má fungovat i samostatně, otevřená dvojklikem.
2. Připiš záznam do `assets/games.js`. Kategorie a štítky se ve filtrech objeví samy.

## Hry

- **Zvířátková škola** (`hry/zviratkova-skola/`): podstatná a přídavná jména, třídění slov a anglická slovíčka se zvířátky. Zadání čte nahlas, vysvětluje odpovědi a obtížnost roste postupně (2 → 3 → 4 možnosti). Slova jsou na začátku skriptu (`ANIMALS`, `TRAITS`, `NOUNS`, `ADJECTIVES`).

## Nasazení

Web běží na GitHub Pages s vlastní doménou `aihry.roud.cz` (DNS záznam CNAME → `tomasroud.github.io`).
