---
views:
    kursrepo:
        region: sidebar-right
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-kursrepo

    redovisa:
        region: sidebar-right
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-redovisa

    byline:
        region: main
        template: anax/v2/block/default
        sort: 2
        data:
            class: "byline"
            meta:
                type: single
                route: block/byline

---
Om
=========================

Denna webbplats har jag byggt med ramverket Anax som en del i kursen [Teknisk webbdesign och användbarhet](https://dbwebb.se/kurser/design-v2) som ingår i kurspaketet  [Webbprogrammering och Databaser, 30hp](https://dbwebb.se/utbildning/webbprogrammering-och-databaser-30hp).

Webbplatsen är skapad av maoh17.

[FIGURE src=image/p111.jpg?w=400 caption="Landmannalaugar, Island."]

Detta innehåll är skrivet i markdown och du hittar innehållet i filen `content/om.md`.
