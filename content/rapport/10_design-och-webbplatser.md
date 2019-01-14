---
---
Design och webbplatser
=========================

Denna rapport är en analys av hur designen påverkar laddningstider för webbplatser som säljer väggkonst på webben.


Urval
-----------------------

Jag har valt att undersöka samma fem webbplatser som i uppdrag ett.

De fem webbplatserna är:

* [Fotografiska](https://www.fotografiska.com/sto/edition/)
* [Printler](https://printler.com/sv/)
* [Fine Art America](https://fineartamerica.com)
* [JUNIQE](https://www.juniqe.com)
* [YellowKorner](http://www.yellowkorner.com/se-en/home)

**Fotografiska** (Sverige) är en av världens största samlingsplatser för fotografi. Fotografiska Edition är unik och högkvalitativ fotokonst som säljs i deras webshop.

**Printler** (Sverige) beskriver sig som marknadsplatsen för väggkonst.

**Fine Art America** (USA) är världens största marknadsplats för konst som säljs som print-on-demand.

**JUNIQE** (Tyskland) säljer prisvärd väggkonst av konstnärer från hela världen.

**YellowKorner** (Frankrike) har som ambition att vara en ledande utgivare av konstfotografi.


Metod
-----------------------

För de fem webbplatserna har jag gjort mätningar av webbprestanda på dels förstasidan och dels en samlingssida med produkter. Jag har använt två olika verktyg i analysen.

* [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/).
* Firefox Developer Tools.

Resultat
-----------------------

Här nedan är resultat från min studie av de fem webbplatserna.


Fotografiska
-----------------------

![Fotografiska](http://www.student.bth.se/~maoh17/dbwebb-kurser/design/me/redovisa/htdocs/img/fotografiska.jpg "Fotografiska")

#### Mätning med PageSpeed Insights / Developer Tools ####

[https://www.fotografiska.com/sto/edition/](https://www.fotografiska.com/sto/edition/)

* Mobil: 5/100 (långsam)
* Dator 72/100 (genomsnittlig)
* Laddningstid: 5,1 s
* Antalet resurser: 112 st
* Sidans totala storlek: 9,9 MB

[https://www.fotografiska.com/sto/shop/limited-edition/](https://www.fotografiska.com/sto/shop/limited-edition/)

* Mobil: 17/100 (långsam)
* Dator 76/100 (genomsnittlig)
* Laddningstid: 5,7 s
* Antalet resurser: 81 st
* Sidans totala storlek: 3,7 MB

#### Optimering ####

Hur kan det vara så här illa? Pagespeed ger rekommendationen att skicka bilder i ett annat bildformat och att använda bilder i rätt storlek. Jag studerade närmare hur bilden "Flight of the Penguing" skickas som thumbnail. Bilden har formatet 500x333 pixlar och är i png-format med storleken 328 kB. Den borde vara i jpeg-format istället.


Printler
-----------------------

![Printler](http://www.student.bth.se/~maoh17/dbwebb-kurser/design/me/redovisa/htdocs/img/printler.jpg "Printler")

#### Mätning med PageSpeed Insights / Developer Tools ####

[https://printler.com/sv/](https://printler.com/sv/)

* Mobil: 69/100 (genomsnittlig)
* Dator 100/100 (snabb)
* Laddningstid: 5,9 s
* Antalet resurser: 77 st
* Sidans totala storlek: 2,8 MB

[https://printler.com/sv/posters-prints/fotokonst/](https://printler.com/sv/posters-prints/fotokonst/)

* Mobil: 73/100 (genomsnittlig)
* Dator 100/100 (snabb)
* Laddningstid: 4,5 s
* Antalet resurser: 64 st
* Sidans totala storlek: 2,6 MB

#### Optimering ####

Det finns möjlighet att optimera laddningstiden genom att bland annat använda bilder i rätt storlek och att koda bilderna effektivare.


Fine Art America
-----------------------

![Fine Art America](http://www.student.bth.se/~maoh17/dbwebb-kurser/design/me/redovisa/htdocs/img/fineartamerica.jpg "Fine Art America")

#### Mätning med PageSpeed Insights / Developer Tools ####

[https://fineartamerica.com](https://fineartamerica.com)

* Mobil: 23/100 (långsam)
* Dator 69/100 (genomsnittlig)
* Laddningstid: 6,9 s
* Antalet resurser: 166 st
* Sidans totala storlek: 4,7 MB

[https://fineartamerica.com/shop/prints](https://fineartamerica.com/shop/prints)

* Mobil: 36/100 (långsam)
* Dator 90/100 (snabb)
* Laddningstid: 7,2 s
* Antalet resurser: 174 st
* Sidans totala storlek: 3,9 MB

#### Optimering ####

Inläsning av sidan kan göras snabbare framförallt genom att skjuta upp inläsning av bilder som inte används på skärmen, men också genom att använda bilder i rätt storlek.


JUNIQE
-----------------------

![JUNIQE](http://www.student.bth.se/~maoh17/dbwebb-kurser/design/me/redovisa/htdocs/img/juniqe.jpg "JUNIQE")

#### Mätning med PageSpeed Insights / Developer Tools ####

[[https://www.juniqe.com](https://www.juniqe.com)]([https://www.juniqe.com](https://www.juniqe.com))

* Mobil: 33/100 (långsam)
* Dator 96/100 (snabb)
* Laddningstid: 7,3 s
* Antalet resurser: 130 st
* Sidans totala storlek: 5,2 MB

[https://www.juniqe.com/wall-art/prints](https://www.juniqe.com/wall-art/prints)

* Mobil: 30/100 (långsam)
* Dator 87/100 (genomsnittlig)
* Laddningstid: 8,8 s
* Antalet resurser: 144 st
* Sidans totala storlek: 4,3 MB

#### Optimering ####

Inläsning av sidan kan göras snabbare genom att skjuta upp inläsning av bilder som inte används på skärmen. Optimering kan även göras genom att ta bort resurser som blockerar renderingen och att skjuta upp CSS som inte används.


YellowKorner
-----------------------

![YellowKorner](http://www.student.bth.se/~maoh17/dbwebb-kurser/design/me/redovisa/htdocs/img/yellowkorner.jpg "YellowKorner")

#### Mätning med PageSpeed Insights / Developer Tools ####

[http://www.yellowkorner.com/se-en/home](http://www.yellowkorner.com/se-en/home)

* Mobil: 57/100 (genomsnittlig)
* Dator 100/100 (snabb)
* Laddningstid: 3,8 s
* Antalet resurser: 57 st
* Sidans totala storlek: 2,9 MB

[http://www.yellowkorner.com/se-en/l/photographs/](http://www.yellowkorner.com/se-en/l/photographs/)

* Mobil: 56/100 (genomsnittlig)
* Dator 81/100 (genomsnittlig)
* Laddningstid: 5,4 s
* Antalet resurser: 62 st
* Sidans totala storlek: 2,7 MB

#### Optimering ####

Optimering kan göras genom att minska svarstiderna från servern. Inläsning av sidan kan göras snabbare genom att skjuta upp inläsning av bilder som inte används på skärmen.



Analys
-----------------------

Jag kan konstatera att ingen av webbplatserna hade en laddningstid på över 10 sekunder, men att bara en hade en laddningstid på under 5 sekunder. Bästa laddningstid hade printler.com. Printler hade även bäst resultat i PageSpeed Insights så därför utser jag Printler till vinnare i mitt test.

Det finns ett antal optimeringsmöjligheter som verkar vara generella för den här typen av webbplatser. Här är några generella optimeringar som det kan vara värt att titta lite extra på:

* Skicka bilder i ett annat bildformat.
* Använda bilder i rätt storlek.
* Koda bilderna effektivare.
* Skjuta upp inläsning av bilder som inte används på skärmen.
* Ta bort resurser som blockerar renderingen.
* Skjuta upp CSS som inte används.

Det är inte helt överskande att mycket av prestandaproblemen beror på bildhanteringen. Det handlar om webbplatser som har mycket bilder och där bilderna är i fokus för användaren.


Referenser
-----------------------

[Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)


Övrigt
-----------------------

av Magnus Ohlin (maoh17)

Detta innehåll är skrivet i markdown och du hittar innehållet i filen `content/rapport/10_design-och-webbplatser.md`.
