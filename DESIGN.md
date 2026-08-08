# DESIGN.md — PANOPRO (panopro.cz) — fast-path

## Barvy (z design-styles.json + screenshotů)
- Primární akcent: `#41597B` (modrošedá — tlačítka, plné plochy)
- Sekundární akcenty: `#39538C` (sytější modrá), `#1F3647` (tmavá petrolejová)
- Hero gradient: světle modrošedá → `#5B79A6`-ish (viz scroll-000) s blueprint podkresem
- Pozadí světlé: `#FFFFFF`, `#F4F4F4` · Pozadí tmavé: `#212121`, `#000000`
- Text: `#333333` / `#4E4E50` na světlé, `#FFFFFF` na modré/tmavé
- Neutrální: `#888B8D`

## Typografie
- Nadpisy: **Barlow** 700–900, VERZÁLKY, bílé na modré / `#1F3647` na bílé (viz „PASPORT STAVBY", „JAK VZNIKÁ PASPORT STAVBY?")
- Podnadpisy: Barlow 400–600, verzálky, menší
- Běžný text: Open Sans 400 / Barlow 400
- Čísla/statistiky: Barlow 800+

## Komponenty
- Tlačítka: hranatá (radius 2px), plná `#41597B` s bílým textem, nebo 2px outline
- Stíny: jemné (`6px 6px 9px rgba(0,0,0,.2)`)
- Vizuální motivy: 3D modely budov (béžová/bílá), mračna bodů, 2D výkresy (čárová grafika), blueprint podklad s nízkou opacitou

## Do's
- Verzálkové Barlow nadpisy, modrý gradient s blueprint texturou, reálné fotky/vizualizace z assets/
- Čísla jako hero prvky (500+ projektů, 5 mm, 5 dnů)
- CTA: „Kalkulace zdarma" na `#41597B`

## Don'ts
- Žádné cizí barvy (žluté/zelené WP presety = balast šablony, nepoužívat)
- Žádné kulaté rohy > 4px, žádné playful prvky — věcný, inženýrský tón
- Nepoužívat swiper-icons/ETmodules (ikonové fonty šablony)
