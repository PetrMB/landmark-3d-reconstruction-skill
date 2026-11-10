# Výšky, terén a zdroje

## Postup

1. Najdi místo a ověř identitu stavby, období a rozsah areálu. Zjisti rozměr z důvěryhodného plánu nebo měření a porovnej obrys s ortofotem a fotografiemi. Katastrální hranice parcely není automaticky obrys stavby ani prezentační základny.
2. Stáhni přiměřený výřez výškopisu a zaznamenej dataset, verzi nebo datum pořízení, oblast, rozlišení, uváděnou přesnost, licenci a vodorovný i výškový referenční systém. Pro každý zdroj zjisti skutečná metadata; nespoléhej na předpoklad, že všechna data používají stejné osy či výškový systém.
3. Reliéf (DTM/DEM zemského povrchu bez budov a vegetace) slouží k návrhu terénu. Povrchový model (DSM) zahrnuje budovy a vegetaci. V místech u budovy zkontroluj interpolaci, zdi, terasy a schody proti fotografiím: raster nebo TIN mohou detail vyhladit či chybně klasifikovat.
4. Pro hrubý odhad výšky vyber několik bodů na patě budovy a na střeše nebo vrcholu v DMP/DSM a porovnej je s DMR/DTM ve stejném systému a jednotkách. Rozdíl odpovídajících nadmořských výšek je odhad výšky nad terénem. Při svažitém terénu uveď, ke kterému místu paty se vztahuje. Ověř, že horní bod neleží na stromu či jiné stavbě. Rozlišení, datum, stíny a klasifikace omezují přesnost; tenká věž nemusí být spolehlivě zachycena.
5. Uveď převod souřadnic a výšek i původ lokálního souřadnicového systému modelu; velké globální souřadnice v Blenderu mohou zhoršit přesnost. V závislosti na skutečných datech ověř pořadí os, znaménka, jednotky, horizontální projekci a vertikální datum. Převod mezi různými výškovými systémy proveď vhodnou transformací, nikoli odhadem konstanty bez podkladu.
6. Porovnej výsledek s více fotografiemi, plánem a známými rozměry. Výškové modely pomáhají s celkovou hmotou, ale samy nedokazují přesný tvar střechy, věže ani historický stav.

## Česká republika

- [Otevřená data Zeměměřického úřadu](https://ags.cuzk.gov.cz/opendata/) — přístup k DMR 5G, DMP 1G a dalším datům, včetně služeb a výřezů. DMR 5G modeluje terén; DMP 1G zahrnuje také stavby a vegetaci. Na stránce ověř aktuální dostupnost, formáty a podmínky použití.
- [DMR 5G: popis služby](https://ags.cuzk.gov.cz/arcgis2/rest/services/dmr5g/ImageServer/info/iteminfo) — výšky v systému Balt po vyrovnání (Bpv), deklarovaná střední chyba výšky 0,18 m v odkrytém a 0,3 m v zalesněném terénu. Tyto údaje nejsou zárukou přesnosti jednotlivého bodu.
- [Analýzy výškopisu ČÚZK](https://ags.cuzk.gov.cz/av/) — průzkum výškopisu a profilů; pro reprodukovatelnou práci zaznamenej použitou vrstvu a místo.
- [Geoportál ČÚZK](https://geoportal.cuzk.gov.cz/) — ortofoto, mapové služby a metadata. Ortofoto a obrys budovy se mohou lišit vlivem data pořízení, zákrytu a geometrie.
- [Památkový katalog NPÚ](https://pamatkovykatalog.cz/) — identifikace památky, popisy a případná dokumentace; ověřuj konkrétní objekt a práva k obrazům.

## Další země

- [USGS 3DEP](https://www.usgs.gov/3d-elevation-program/about-3dep-products-services) a [LidarExplorer](https://www.usgs.gov/tools/lidarexplorer) pro USA; vybírej skutečně dostupný produkt a čti jeho metadata.
- Jinde nejprve hledej národní zeměměřický úřad, otevřená data místní správy a památkový ústav. Celosvětové výškopisy mohou být příliš hrubé pro jednotlivou budovu. Podmínky dat a fotografií ověřuj jednotlivě.
