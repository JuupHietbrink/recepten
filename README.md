# Pasta, sushi & wijn

Een kookboek voor twee goede vrienden: twaalf klassieke gerechten uit de Italiaanse en Japanse keuken, drie techniekhoofdstukken en bij elk gerecht de wijn die erbij hoort.

**Voorproefje:** https://juuphietbrink.github.io/recepten/

## Inhoud

### Technieken
- [Verse pasta: de basis](technieken/verse-pasta.md)
- [Sushi: rijst en vis](technieken/sushi-basis.md)
- [Wijn bij het eten](technieken/wijngids.md)

### Italiaans
1. [Vitello tonnato](recepten/italiaans/vitello-tonnato.md) — Piemonte · Roero Arneis
2. [Tagliatelle al ragù alla bolognese](recepten/italiaans/tagliatelle-al-ragu-alla-bolognese.md) — Bologna · Lambrusco di Sorbara
3. [Lasagne verdi alla bolognese](recepten/italiaans/lasagne-verdi-alla-bolognese.md) — Bologna · Lambrusco Grasparossa
4. [Pappardelle al ragù di anatra](recepten/italiaans/pappardelle-al-ragu-di-anatra.md) — Toscane · Chianti Classico Riserva
5. [Cacio e pepe](recepten/italiaans/cacio-e-pepe.md) — Rome · Frascati Superiore
6. [Tortelli di ricotta e spinaci](recepten/italiaans/tortelli-di-ricotta-e-spinaci.md) — Emilia/Toscane · Soave Classico
7. [Risotto ai funghi porcini](recepten/italiaans/risotto-ai-funghi-porcini.md) — Piemonte/Lombardije · Barbera d'Alba
8. [Ossobuco alla milanese](recepten/italiaans/ossobuco-alla-milanese.md) — Milaan · Valtellina Superiore
9. [Tiramisù](recepten/italiaans/tiramisu.md) — Treviso · Recioto di Soave

### Japans
1. [Nigiri en hosomaki](recepten/japans/nigiri-en-hosomaki.md) — Junmai Ginjo / Champagne Blanc de Blancs
2. [Temaki-avond](recepten/japans/temaki-avond.md) — Champagne Brut
3. [Chirashizushi](recepten/japans/chirashizushi.md) — Riesling Kabinett

## Het boek afdrukken

De site is opgemaakt als A4-pagina's met zwarte achtergrond en witte letters. Open een pagina, kies **Afdrukken** (of ⌘P), stel in op A4, marges *geen*, en zet *achtergrondafbeeldingen afdrukken* aan. Sla op als PDF voor de drukker.

## Structuur

```
_config.yml          Jekyll-configuratie (GitHub Pages)
_layouts/            default.html (schil) en recipe.html (receptpagina met foto)
_data/credits.json   Fotobronnen en licenties
assets/css/book.css  Boeklayout, incl. @media print voor A4
assets/img/          Foto's (Wikimedia Commons, CC)
technieken/          Techniekhoofdstukken
recepten/            Recepten per keuken
```

Elke receptpagina heeft front matter met `title`, `subtitle`, `image`, `section` en `order`; de index wordt daaruit gegenereerd.

## Lokaal bekijken

```sh
bundle install
bundle exec jekyll serve
```

## Fotoverantwoording

Zie [fotoverantwoording](https://juuphietbrink.github.io/recepten/fotoverantwoording.html). Alle foto's komen van Wikimedia Commons onder CC-licenties; neem de bronvermelding op in het gedrukte boek.
