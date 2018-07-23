---
title: Formuláře
permalink: "/guidelines/forms.html"
layout: page
type: detail
group: components
description: Formuláře umožňují uživatelům zadávat data pro použití aplikací. Používají se k získávání informací. Duležité je aby uživatelé nebyli při jeho vyplňování rušeni okolními vlivy. Při navrhování formulářů je důležité myslet na jejich strukturu. Jednotlivé prvky se řídí pravidly, které jsou sepsány v sekci komponenty.
---

## Použití

Všechny formuláře se skládají ze 6 prvků:

1. Označení (Label) - Krátké označení, které by mělo uvést jaké informace se mají do pole vyplnit. Zrovnáváme doleva.
2. Pole pro vyplnění (Field)  - Místo kam uživatelé vkládají text.
3. Zástupný text (Placeholder text) - Dává informaci jak by pole mělo být používáno (např. "Začněte psát"). Používejte pouze tam, kde je třeba objasnění, snažte se jej nepoužívat nadměrně.
4. Nápověda (Help text) - Poskytuje pomoc při vyplňování pole. Text nápovědy je nepovinný.
5. Akce (Action) - Umožnit uživatelům odeslat formulář.
6. Validace (Validation) - Zajišťuje, aby údaje odeslané uživatelem odpovídaly přijatelným parametrům.

![Schéma formulářových prvků](/mv-design-system/images/form_schema.png)

## Logika formulářových prvků

[Přepínače (Radio buttons)](/mv-design-system/components/radio-button.html) - se používají, když je seznam dvou nebo více možností, které se navzájem vylučují a uživatel musí zvolit přesně jednu volbu. Jinými slovy, klepnutím na nevybraný přepínač zrušíte volbu libovolného jiného tlačítka v seznamu.

 - se používá, když je pouze jedna možnost

[Zaškrtávací pole (Checkboxes)](/mv-design-system/components/checkbox.html) - se používají, když existují seznamy voleb a uživatel může vybrat libovolný počet možností, včetně nuly, jednoho nebo několika. Jinými slovy, každé zaškrtávací políčko je nezávislé na všech ostatních zaškrtávacích polích v seznamu, takže zaškrtnutím jednoho políčka se nezruší ostatní. 

[Samotné zaškrtávací políčko (Toggle)](/mv-design-system/components/toggle.html) nebo přepínač lze použít pro jednu možnost, kterou může uživatel zapnout nebo vypnout.

U polí, ve kterých je požadován jediný výběr a existuje mnoho možností, zvážit použití prvku [Rozbalovací seznam (Select box)](/mv-design-system/components/selectbox.html).

![Schéma použítí formulářových prvků](/mv-design-system/images/schema_inputy.png)

## Obecná pravidla

### Udržte formulář krátký

Buďte co nejpřísnější při navrhování formulářů. Přemýšlejte o každém poli a jakou hodnotu budou údaje poskytovat. Co získáte shromažďováním těchto informací?
Zjednodušujte formuláře tak, že je přepíšete, případně je také možné rozdělit formulář do více kroků. Při strukturování formuláře zvažte jeho kontext. Pokud spolu informace souvisí je možné je jich na stránku umístit víc. Jednotlivé kroky formuláře musí vždy obsahovat související infromace. Jednotlivé kroky pojmenujte srozumitelně tak, aby z názvu bylo patrné co jeobsahem daného kroku.

### Povinná a nepovinná pole

* Požadujte po uživatelích ty údaje, které jsou bezprostředně potřebné pro spuštění služby. 
* Pro nepovinné údaje je potřeba tyto pole označit jako nepovinné (nepovinný údaj).
* Povinná pole se neoznačují hvězdičkou.

#### Začněte tím, že se zeptáte:

* Je to pro nás něco, co je pro nás cenné?
* Je to taková informace, která je tak cenná, že stojí za to zabránit tomu, aby uživatel pokračoval, pokud se rozhodne ji neposkytnout?

### Označení datového pole (Label)

* Každý formulářový prvek má přiřazený výstižný název.
* Názvy datových polí se skrývají pouze v případě, že jsou vůči okolnímu kontextu nepotřebné.
* Názvy datových polí musí být zarovnané nad pole, které označují.
* Názvy datových polí by měly být krátké, srozumitelné a výstižné.
* Je potřeba se vyhýbat dvojtečkám za názvem.
* Názvy musí být přiřazené k polím pomocí atributu for.

### Nápověda (Help text)

* Text nápovědy je relevantní informace, která pomáhá uživateli při vyplňování pole.
* Používejte vždy tam, kde lze předpokládat komplikace s vyplnění pole.
* Vyhněte se nadměrnému užívání u jednoznačných názvů (např. jméno).
* Text nápovědy je zobrazen vždy pod názvem datového pole. 
* Text v nápovědě musí být jednoznačně sděleno co má uživatel v daném prvku vyplnit nebo zvolit a jak sním má uživatel zacházet.

### Zástupný text (Placeholder text)

* Zástupný text zmizí poté, co užovatel začne zadávat data do textové pole.
* Neměl by obsahovat zásadní informace o tom, jaká data má uživatel vyplnit.
* V případě, že jde o zásadní informace pro vyplnění, nabízí se použití nápovědy.
* Text napiště jako přímý příkaz bez interpunkce.

## Chyby a validace

### Chybové hlášky

#### Přehled o chybách

Doporučujeme ověřovat údaje průběžne, ještě před odeslání samotného formuláře. Pro uživatele může být těžké zorientovat se na stránce po zobrazení chyby. Obzvláště pokud se vyskytlo více chyb současně. Zobrazujte přehled o chybách v horní části stránky tak, aby byl viditelný, když se stránka aktualizuje a ihned jej dokázala přečíst pomocná zařízení. Je důležité přidat nadpis, který upozorní uživatele na chybu. V přehledu použijte odkaz, který povede na každé datové pole, kde byla zaznamenána chyba.

#### Zvyýraznění chyb ve formulářích

Pro každou chybu:

* Napište zprávu, která pomůže uživateli pochopit, proč se chyba vyskytla a jak by ji měl odstranit.
* Zprávu vložte do prvku <label> nebo <legend> k dané otázce.
* Chybovou hlášku zobrazujte pod datovým polem.
* Pro zvýraznění chybové hlášky použijte červenou barvu.

















