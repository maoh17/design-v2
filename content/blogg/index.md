---
views:
    main:
        template: anax/v2/article/default
        data:
            class: blog

    byline: false
    block-about: false
    article-toc: false

    blog-list:
        region: main
        template: anax/v2/blog-list/default
        sort: 2
        data:
            dateFormat: j F Y
            meta:
                type: toc
                orderby: publishTime
                orderorder: desc

    blog-toc:
        region: sidebar-right
        template: anax/v2/blog-toc/default
        sort: 2
        data:
            meta:
                type: copy
                view: blog-list

---
Dagens bild
===========================

Här är några bilder från min vandring längs [Gröna Bandet](https://www.vitagronabandet.se/sv-SE). Jag vandrade 152 mil längs hela den skandinaviska fjällkedjan från Treriksröset till Grövelsjön under 99 dagar hösten 2016.

Fotona är tagna med min systemkamera, en Canon EOS 6D med objektiv EF 24-70mm f/4L IS USM.
