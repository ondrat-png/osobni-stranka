# Osobní stránka – Přístupnost

## Media rules

| Pravidlo | Co se mění a proč |
| :--- | :--- |
| `@media (min-width: 40em / 60em / 80em)` | Přizpůsobuje rozvržení stránky, navigace a karet od úzkých mobilních displejů po široké monitory (přístup mobile-first), aby nevznikal vodorovný posuvník. |
| `@media (prefers-color-scheme: dark)` | Přepne barevné proměnné na tmavé pozadí a světlý text, aby stránka neoslňovala při práci v tmavém prostředí. |
| `@media (prefers-contrast: more)` | Zvýší kontrast barev na úroveň WCAG AAA, zesílí ohraničení prvků a podtrhne odkazy pro lepší čitelnost. |
| `@media (prefers-reduced-motion: reduce)` | Vypne plynulé posouvání stránky (`scroll-behavior: auto`) a zkrátí animace i přechody na minimum, aby nezpůsobovaly nevolnost nebo nesoustředěnost. |
| `@media (prefers-reduced-transparency: reduce)` | Odstraní průhlednost a rozmazání pozadí karet (`backdrop-filter: none`), aby text zůstával vždy ostře čitelný. |
| `@media (forced-colors: active)` | Nahradí vlastní barvy systémovými klíčovými slovy (`Canvas`, `CanvasText`, `LinkText`, `ButtonBorder`, `Highlight`), aby zůstaly zachovány okraje a fokus v režimu vysokého kontrastu systému. |
| `@media (prefers-color-scheme: dark) and (prefers-contrast: more)` | Kombinuje tmavý režim s maximálním kontrastem (čistě černé pozadí, bílý text a žluté odkazy) pro uživatele vyžadující obojí. |