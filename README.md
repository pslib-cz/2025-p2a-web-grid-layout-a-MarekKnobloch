# Zadání – Seznámení s CSS Grid Layout pomocí Grid Area

## Cíl
Vaším úkolem je porozumět základům CSS Grid Layout a naučit se pracovat s pojmem `grid-template-areas`, který umožňuje jednoduše definovat rozvržení stránky pomocí pojmenovaných oblastí. Především se zaměříte na úpravy a doplnění CSS v sekci `@layer layout { }` ve stylovém souboru.

## Úvod
V CSS souboru máte již předpřipravenou strukturu grid layoutu, který používá několik oblastí:
- header
- nav
- main
- aside
- footer

Tyto oblasti jsou přiřazeny k jednotlivým částem stránky (navigace, hlavní obsah, postranní panel apod.) pomocí příkazu `grid-area`.

## Zadání
1. Prostudujte stávající definici `.layout` a oblasti v sekci `@layer layout { }`, kterou najdete ve stylovém souboru `style.css`.
2. V sekci `@layer layout { }` najdete připravené definice, ale část musíte doplnit sami:
   - Doplnit další hodnoty pro `grid-template-columns`, `grid-template-areas`, aby layout byl responsivní.
   - Vytvořit vlastní kombinace oblastí pro různá šířková rozlišení (media queries).
3. Zaměřte se na to, aby při úpravách layout zůstal přehledný a oblasti správně přiřazené k jednotlivým HTML prvkům.
4. Otestujte své změny v prohlížeči a ověřte, že se layout přizpůsobuje různým šířkám obrazovky (mobil, tablet, desktop).

## Doporučení
- Použijte stávající CSS jako vodítko.
- Vyzkoušejte další hodnoty a uspořádání grid oblastí.
- Přečtěte si dokumentaci k CSS Grid a `grid-template-areas` (můžete použít MDN).

---

Váš stylový soubor obsahuje část, kterou máte doplnit, označenou `@layer layout { }`. Nic jiného neměňte, pouze v této části proveďte své úpravy a doplnění.

