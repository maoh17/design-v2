---
title: "Min test-sida"
views:
    kursrepo:
        region: sidebar-left
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
---
Test
=========================

Här är lite test av hur Markdown kan generera HTML.

Detta innehåll är skrivet i markdown och du hittar innehållet i filen `content/test.md`.

Rubrik nivå 1
====================

Rubrik nivå 2
---------------------

### Rubrik nivå 3

> Block citat

*Kursiv stil*

**Fet stil**

Lista:

*   Blå
*   Gul
*   Grön

Numrerad lista:

1.  Röd
2.  Grön
3.  Blå

Ett exempel på en [länk](https://dbwebb.se/kurser/design-v2).

Bild:

![Kalle Anka](http://www.student.bth.se/~maoh17/dbwebb-kurser/design/me/redovisa/htdocs/img/kalleanka.jpg "Titel")

`Kod`
