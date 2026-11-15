# TOP CELEBRITY – statická pracovní verze

## Obsah
- Kategorie a 49 původních jmen získaných z veřejných kategorií Webnode.
- Profily s editovatelnými poli a místem pro portréty a galerii.
- Redakční administrace s exportem/importem JSON.
- Partnerské bannery, Stats4U a AdSense.

## Administrace a publikování
GitHub Pages je statický hosting. Administrace proto nemůže bezpečně zapisovat do repozitáře ani centrální databáze. Úpravy v prohlížeči exportuj jako `content.json` a nahraj do `data/content.json` v repozitáři. Není zde žádné výchozí PIN heslo; přístup k admin.html není zabezpečen serverově. Nepoužívej ji pro citlivá data.

## Fotografie
Profily mají pole pro cestu k portrétu a galerii. Fotografie můžeš doplnit do `assets/` a cestu zadat v administraci. Před publikací ověř licenci a právo k užití.

## Nasazení
Nahraj obsah ZIPu do kořene GitHub repozitáře. Doména je nastavena v CNAME na `topcelebrity.kolobeznik.cz`.
