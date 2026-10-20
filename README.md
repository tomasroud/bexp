# Zvířátková škola

Hra pro malé děti na procvičování podstatných jmen, přídavných jmen a anglických slovíček se zvířátky. Je to jediný soubor `index.html`: stačí ho otevřít v prohlížeči (dvojklikem), nic se neinstaluje.

## Hry

- **Co je na obrázku?** – dítě vidí zvířátko a vybere správné slovo (podstatná jména, čtení).
- **Jaké je zvířátko?** – „Jaká je žirafa?“ → *vysoká* (přídavná jména ve správném rodě).
- **Kdo? Co? Nebo jaký?** – třídění slov do košíků podstatné / přídavné jméno.
- **Anglická slovíčka** – hlas řekne anglické slovo, dítě najde obrázek.

Za každé dokončené kolo přibude nálepka do alba (ukládá se v prohlížeči).

## Z čeho návrh vychází

- **Zadání se čte nahlas** (předčítání zabudované v zařízení), aby hru zvládlo i dítě, které ještě nečte.
- **Zpětná vazba vysvětluje**, místo aby jen pípla: „Slon není malý. Zkus to znovu.“ Výzkum ukazuje, že vysvětlující zpětná vazba vede k přesnějším odpovědím než samotný zvuk.
- **Obtížnost roste postupně**: v každém kole jsou nejdřív 2 možnosti, pak 3, nakonec 4.
- **Velká tlačítka**, nejvýš 4 možnosti na obrazovce, žádné trestání za chybu.

Zdroje: [Harvard – Reach Every Reader](https://reacheveryreader.gse.harvard.edu/which-mobile-app-feedback-and-leveling-designs-best-scaffold-preschool-learning), [UC Irvine](https://news.uci.edu/2018/09/19/most-preschool-math-literacy-apps-not-designed-to-help-children-learn-uci-study-finds), [Google – Designing engaging apps for kids](https://developers.google.com/building-for-kids/designing-engaging-apps).

## Úpravy

Slova a zvířátka jsou na začátku skriptu v `index.html` (`ANIMALS`, `TRAITS`, `NOUNS`, `ADJECTIVES`). Obrázky jsou emoji, takže fungují bez internetu. Bez internetu se jen použije náhradní písmo.

Když aplikace nemluví, je potřeba v nastavení systému doinstalovat český (a pro slovíčka anglický) hlas.
