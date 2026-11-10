---
name: landmark-3d-reconstruction
description: Vytvářej a průběžně opravuj editovatelné 3D modely skutečných staveb a landmarků podle fotografií, map a výškopisných dat; používej při modelování i kontrole shody se skutečností.
---

# Rekonstrukce landmarku podle podkladů

Vytvoř rozpoznatelný a editovatelný model odpovídající dostupné evidenci. Zvol nástroj podle zadání (např. Blender); atraktivní render, geometricky správná síť ani úspěšný slicing samy nedokazují architektonickou věrnost.

## Podklady a měřítko

- Urči konkrétní stavbu, zobrazené období, hranice areálu, účel, požadované výstupy a míru detailu. U rozpracovaného projektu nejprve zjisti aktuální master, rozhodnutí a nevyřešené připomínky.
- Shromáždi fotografie z co nejvíce stran, z výšky i od země, detaily, ortofoto, mapové obrysy, historické plány a případné zaměření. Eviduj odkaz či cestu, autora, licenci, datum pořízení, směr pohledu a použití. Podklady z různých období neslučuj bez vysvětlení.
- Doložené měření má přednost před odhadem z obrázku. Urči jednotky, orientaci a referenční rozměr; u modelu ve skutečném měřítku ulož georeferenční informace a převod do lokálních souřadnic. Neoznačuj rozměry za přesné, pokud nejsou zaměřené.
- K určení výšek a terénu vyhledej vhodná otevřená data pro danou zemi a zkontroluj jejich datum, přesnost, horizontální a výškový referenční systém a licenci. V ČR použij dle vhodnosti ČÚZK DMR 5G pro reliéf a DMP 1G pro povrch s objekty, ortofoto a další podklady; viz [výšky a zdroje](references/vysky-a-zdroje.md). Výška vrcholu nad mořem není výška budovy: tu lze orientačně získat rozdílem povrchu a paty ve stejném referenčním systému. Nezaměňuj střechu s vegetací ani zpracované hodnoty za geodetické zaměření.

## Model a kontrola ve smyčce

1. Sestav půdorys a polohy částí, hlavní výšky a siluety, střechy a terén. Pak teprve rozpracuj fasády, otvory, schodiště, římsy a dominantní detaily. Zachovej asymetrie a návaznost částí.
2. Pro každou významnou stranu a problematický detail najdi vhodnou fotografii. Přibliž polohu kamery, ohnisko, směr a výšku pohledu; porovnej fotografii a model vedle sebe nebo průhledným překryvem. Srovnej charakteristické body, obrys, vzájemné poměry, počet a rozmístění otvorů, sklony střech, návaznosti a terén. Perspektivu nepovažuj za rovnoměrné měřítko.
3. Sepiš konkrétní nesrovnalosti s odkazem na zdroj a důvěrou v interpretaci. Oprav nejprve polohu a tvar, potom detaily a materiály. Nejasný nebo zakrytý prvek označ jako odhad; nepřidávej smyšlené detaily jako skutečnost.
4. Po opravě vytvoř nové kontrolní záběry ze stejného směru a alespoň jednoho dalšího relevantního směru, ověř sousední části a projdi celý obvod. Když podklady nestačí, vyhledej další fotografie nebo měření a zbývající nejistotu předej uživateli. Pokračuj v revizích podle zadání a dostupných důkazů.
5. Ulož zdrojový podklad, předchozí a novou verzi modelu a záznam: místo, problém, reference, změna, ověření a nejistota. Nový důkaz může vyvrátit starší výklad. Konkrétní příklady a postup viz [porovnání a opravy](references/fotografie-a-opravy.md).

## Výstup a volitelný tisk

Zachovej původní podklady a editovatelný master; exporty a případnou tiskovou kopii odděl. Předej srovnávací pohledy, zdroje a licence, provedené opravy, odhady, jednotky a postup kontroly. Pokud je požadován tisk, přizpůsob kopii měřítku a tiskárně, ověř spoje, rozměry, uzavřenost a spodní plochu, znovu importuj export a zkontroluj vrstvy ve sliceru. Uveď úpravy nutné pro tisk a samostatně stav digitální kontroly, přenosu a fyzického výtisku.
