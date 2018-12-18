---
---
Laddningstid
=========================

Denna uppgift handlar om att utvärdera webbplatsers laddningstid och användbarhet.

Urval
-----------------------

Jag har valt att undersöka samma tre webbplatser som i den föregående uppgiften om färgschema. Urvalet har jag valt utifrån en kombination av kommersiell framgång och ett personligt intresse.

Alla tre är framgångsrika svenska e-handelsbutiker som har många bilder på sina webbplatser. Även om de säljer olika slags produkter tycker jag att det är relevant att göra en jämförelse.

De tre webbplatserna är:

* [danielwellington.com](https://www.danielwellington.com/se/)
* [desenio.se](https://desenio.se)
* [stellarequipment.com](https://www.stellarequipment.com/se/)


Metod
-----------------------

För de tre webbplatserna har jag valt ut tre sidor. Första sidan, en samlingssida och en produktsida. För var och en av dessa sidor har jag gjort mätningar av webbprestanda med två olika verktyg.

* [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/).
* Firefox Developer Tools.

För varje sida har jag gjort tre mätningar i devtools och tagit ett snitt av mätvärdena.


Resultat
-----------------------

Här nedan är resultat från min studie av de tre webbplatserna.

Jag har samlat all mätdata i ett [kalkylark](https://docs.google.com/spreadsheets/d/1sDH7sRNs06QC5LVJrQoYgIOkPFcw_Pmc9LvILSAWew0/edit?usp=sharing).


danielwellington.com
-----------------------

![Daniel Wellington](http://www.student.bth.se/~maoh17/dbwebb-kurser/design/me/redovisa/htdocs/img/danielwellington1.png "Daniel Wellington")

#### Mätning med PageSpeed Insights / Developer Tools ####

[https://www.danielwellington.com/se/](https://www.danielwellington.com/se/)

* Mobil: 60/100 (genomsnittlig)
* Dator 100/100 (snabb)
* Laddningstid: 9,6 s
* Antalet resurser: 95 st
* Sidans totala storlek: 2,6 MB

[https://www.danielwellington.com/se/mens-watches/](https://www.danielwellington.com/se/mens-watches/)

* Mobil: 59/100 (genomsnittlig)
* Dator 100/100 (snabb)
* Laddningstid: 9,9 s
* Antalet resurser: 127 st
* Sidans totala storlek: 4,1 MB

[https://www.danielwellington.com/se/dw-bundle-classic-sheffield-36-rose-gold-st-mawes-18-rose-gold-strap](https://www.danielwellington.com/se/dw-bundle-classic-sheffield-36-rose-gold-st-mawes-18-rose-gold-strap)

* Mobil: 56/100 (genomsnittlig)
* Dator 100/100 (snabb)
* Laddningstid: 9,5 s
* Antalet resurser: 78 st
* Sidans totala storlek: 1,6 MB

#### Optimering ####

Inläsning av sidan kan göras snabbare genom att skjuta upp inläsning av bilder som inte används på skärmen. Optimering kan även göras genom att ta bort resurser som blockerar renderingen.


desenio.se
-----------------------

![Desenio](http://www.student.bth.se/~maoh17/dbwebb-kurser/design/me/redovisa/htdocs/img/desenio1.png "Desenio")

#### Mätning med PageSpeed Insights / Developer Tools ####

[https://desenio.se/](https://desenio.se/)

* Mobil: 72/100 (genomsnittlig)
* Dator 100/100 (snabb)
* Laddningstid: 3,6 s
* Antalet resurser: 76 st
* Sidans totala storlek: 2,2 MB

[https://desenio.se/sv/artiklar/prints-posters/fotografier-prints/index.html#{}](https://desenio.se/sv/artiklar/prints-posters/fotografier-prints/index.html#{})

* Mobil: 67/100 (genomsnittlig)
* Dator 100/100 (snabb)
* Laddningstid: 4,8 s
* Antalet resurser: 70 st
* Sidans totala storlek: 1,1 MB

[https://desenio.se/sv/artiklar/lion-posters.html](https://desenio.se/sv/artiklar/lion-posters.html)

* Mobil: 72/100 (genomsnittlig)
* Dator 100/100 (snabb)
* Laddningstid: 4,9 s
* Antalet resurser: 67 st
* Sidans totala storlek: 1,1 MB

#### Optimering ####

Inläsning av sidan kan göras snabbare genom att använda bilder i rätt storlek. Optimering kan även göras genom att ta bort resurser som blockerar renderingen.


stellarequipment.com
-----------------------

![Stellar Equipment](http://www.student.bth.se/~maoh17/dbwebb-kurser/design/me/redovisa/htdocs/img/stellar1.png "Stellar Equipment")

#### Mätning med PageSpeed Insights / Developer Tools ####

[https://www.stellarequipment.com/se/](https://www.stellarequipment.com/se/)

* Mobil: 8/100 (långsam)
* Dator 47/100 (långsam)
* Laddningstid: 12,4 s
* Antalet resurser: 230 st
* Sidans totala storlek: 7,9 MB

[https://www.stellarequipment.com/se/men-s/shell/shell-jackets](https://www.stellarequipment.com/se/men-s/shell/shell-jackets)

* Mobil: 10/100 (långsam)
* Dator 62/100 (genomsnittlig)
* Laddningstid: 14,2 s
* Antalet resurser: 262 st
* Sidans totala storlek: 3,2 MB

[https://www.stellarequipment.com/se/m-stellar-shell-jacket-blue](https://www.stellarequipment.com/se/m-stellar-shell-jacket-blue)

* Mobil: 8/100 (långsam)
* Dator 37/100 (långsam)
* Laddningstid: 15,4 s
* Antalet resurser: 302 st
* Sidans totala storlek: 10,7 MB

#### Optimering ####

Inläsning av sidan kan göras mycket snabbare genom att skjuta upp inläsningen av bilder som inte visas på skärmen och genom att använda bilder i rätt storlek. Optimering kan även göras genom att ta bort resurser som blockerar renderingen.


Analys
-----------------------

Daniel Wellington och Desenio klarar sig ganska bra för dator medan det finns förbättringspotential för mobilt. Stellar har riktigt dåliga laddningstider. Det tar 5 sekunder för första uppritningen av innehåll för en produktsida och närmare 20 sekunder innan allt är klart.  

Gemensamt för alla tre webbplatserna är att optimering kan göras genom att ta bort resurser som blockerar renderingen. Att skjuta upp inläsningen av bilder som inte visas på skärmen och genom att använda bilder i rätt format och storlek kan också minska laddningstiden.


#### Slutsats: ####

Jag rangordnar webbplatserna avseende laddningstid enligt följande:

1. Desenio
2. Daniel Wellington
3. Stellar Equipment

Desenio har klart snabbast laddningstider på ca 3-5 s. Stellar har överlägset sämst betyg i PageSpeed och har också sämst laddningstider i devtools.

Jag tycker att den totala laddningstiden för en sida inte bör överstiga 5 sekunder och det klarar bara Desenio i mitt test. Något som också spelar en stor roll för hur man upplever laddningstiden är tiden till den första bilden och texten ritats ut. Där tycker jag att alla webbplatserna klarar sig ganska bra så upplevelsen blir därför ändå ganska ok. Stellar ritar upp första bilden och texten ganska snabbt men resten är riktigt långsamt och irrirerande.

Referenser
-----------------------

[PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)


Övrigt
-----------------------

av Magnus Ohlin (maoh17)

Detta innehåll är skrivet i markdown och du hittar innehållet i filen `content/rapport/05_laddningstid.md`.
