---
title: Tlačítko
layout: component-detail
group: components
description: Tlačítka jsou uživateli používána pro spuštění akce.
status: Complete
variations:
- title: Typy tlačítek
  description: Typy tlačítek odstupňované podle důležitosti spouštěné akce.
  pattern: button/button-types.html
- title: Primární tlačítka
  description: Nejdůležitější tlačítko primární akce v různých velikostech.
  pattern: button/button-primary.html
- title: Sekundární tlačítka
  description: Tlačítko sekundární akce v různých velikostech.
  pattern: button/button-secondary.html
- title: Terciární tlačítka
  description: Tlačítko terciární akce v různých velikostech. Doporučená je menší velikost.
  pattern: button/button-terciary.html
---


## Typy tlačítek

Existuje několik druhů tlačítek, které se používají lyší v kontextu použití

| Typ                   | Použití                                                                    |
| ----------------------|------------------------------------------------------------------------------|
| Primární              | Používáme pro spuštění primární akce jako např. vyhledávání, napsání datové zprávy, nahrání nového dokumentu atd... Mělo by bát pouze jednou na stránce. | 
| Sekundární            | Používáme pro sekundární akce jako např. tisk datové zprávy, zobrazení dalšího obsahu apod. | 
| Terciární tlačítko    | Používáme na stránkách s velkým množstvím akcí, kde je potřeba odstupňovat více úrovní. Doporučené je použití ve velikosti "SMALL". | 


## Velikosti tlačítek

Tlačítka můžeme používat v několika různých velikostech. Pro každou stránku je vhodné jiné použití.

| Velikost              | Použití                                                                    |
| ----------------------|------------------------------------------------------------------------------|
| Small                 | Používáme především pro terciární tlačítka nebo tam, kde není dostatek prostoru pro umístění tlačítka normální velikosti. | 
| Normal                | Standardní velikost, se kterou si vystačíte ve většině případů. | 
| Large                 | Vhodné především pro landing-pages s cílem provedení konverze (např. registrace do portálu, spočítání důchodu. apod...) | 

## Disable state

Užíváme tam, kde uživatel nemá povolenou danou akci nebo v případě, že se nacházíme přímo na stránce dané akce.

### Příklad použítí:

![Ukázka použití](/mv-design-system/images/datova_schranka.png "Ukázka použití")

V datové schránce na Portálu občana je použitáý DISABLE BUTTON při psaní zprávy v situaci, kdy akce, kterou tlačítko vyvolává, je právě spuštěná a není ji tedy možné spustit znovu.
