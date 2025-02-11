---
Title: Laddningstid
Description: This is our colors page.
Template: analysis
---

# Loading

Analys av webbplatsers laddningstid och användbarhet
=======================

I denna uppgift ska olika webbplatsers laddningstid och användbarhet analyseras och dokumenteras. Det ska även dras slutsatser om hur laddningstiden och användbarheten påverkar användarupplevelsen.

Urval
-----------------------

Analysen fokuserar på webbplatser inom kategorin e-handel. De utvalda webbplatserna är [Amazon][], [Zalando][] och [ASOS][]. Valet att analysera e-handelswebbplatser baseras på att besökare har höga förväntningar på snabb och smidig funktionalitet när de handlar online. Långa laddningstider riskerar att leda till förlorade kunder, och en tydlig navigation är avgörande för att enkelt hitta produkter. Zalando, ASOS och Amazon är några av de största e-butikerna, vilket innebär att de ställs inför höga krav på att hålla sina webbplatser uppdaterade och snabba.

Metod
-----------------------

Undersökningen inleddes med att dokumentera laddningstider och användarbarhet för de valda webbplatserna. För att samla in och dokumentera data användes PageSpeed Insights, ett verktyg utvecklat av Google för att analysera webbplatsers prestanda. Verktyget ger en prestandapoäng på en skala från 0 till 100 baserat på analyser av den inskickade webbplatsen. Dessa poäng noterades och skrevs in i ett Excel-ark för vidare analys.

Resultat
-----------------------

<iframe title="results" class="frame-container" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRbeBTlBC3cupxeBs1FsdQ67JQs9sHyk7MzpGvTNc7QHmeTmma8T25GUEYcLgdae0R_XUZEfLENu9Vr/pubhtml?widget=true&amp;headers=false"></iframe>

Undersökningen visar hur lång laddningstid de tre olika sidorna har för data. Vissa sidor är bättre än andra på att ladda in data, och det kan bero på allt från högkvalitativa bilder till vilka resurser som används på sidorna.

<img class="reportimage" src="../assets/img/AmazonW.png" alt="AW" />

Amazons webbsida för dator gav ett mycket bra resultat vad gäller både prestanda och tillgänglighet. Webbsidan använder enkla div-element och text, samt undviker högkvalitativa bilder, vilket gör att den är mycket lätt att ladda in. Den är snabb och ger användaren enkel åtkomst till artiklar. Amazons datorversion visar dessutom mycket bättre resultat på First Contentful Paint (FCP) än mobilversionen, vilket innebär att laddningstiden är betydligt kortare på dator. Amazons Total Blocking Time (TBT) var bäst av alla de undersökta webbsidorna för både dator- och mobilversioner, med tider så låga som 80 ms för datorn och 160 ms för mobilen. Även när det gäller Speed Index är datorversionen snabbare än mobilversionen, med ett värde på 2,9 sekunder. Sammantaget hade Amazon den bästa prestandan av alla undersökta webbsidor, både för dator och mobil.

<img class="reportimage" src="../assets/img/ZalandoW.png" alt="ZW" />

Zalando hade generellt dåliga prestandaresultat jämfört med de andra webbsidorna som analyserades. Den sticker ut som den långsammaste sidan i flera mätkategorier. På dator är FCP relativt bra med 0,7 sekunder, men mobilversionen är ganska långsam med 3,2 sekunder. När det gäller TBT presterar Zalando bättre än ASOS, men betydligt sämre än Amazon. TBT för dator är nästan sju gånger högre än Amazons resultat. Zalando har det långsammaste Speed Index i mätningen, särskilt på mobil där 7,4 sekunder är mer än dubbelt så långsamt som ASOS och Amazon. Mobilversionen har en mycket långsam LCP, vilket innebär att stora visuella element tar lång tid att ladda. Datorversionen är bättre. Zalando har den sämsta CLS på mobil, vilket betyder att layouten är instabil och kan leda till en dålig användarupplevelse. Prestandapoängen för Zalando är lägst av de tre webbsidorna, vilket bekräftar att det finns stora optimeringsbehov.

<img class="reportimage" src="../assets/img/AsosW.png" alt="ASW" />

ASOS hade generellt blandade prestandaresultat jämfört med de andra webbsidorna som analyserades. På dator är FCP bra med 0,6 sekunder, medan mobilversionen också presterar relativt bra med 2,2 sekunder. När det gäller TBT har ASOS däremot höga värden, 2 030 ms för dator och 1 500 ms för mobil. Detta är sämre än både Zalando och Amazon. ASOS presterar bättre på Speed Index jämfört med Zalando, men är fortfarande långsammare än Amazon. Mobilversionen har ett Speed Index på 5,5 sekunder, medan datorn når 1,5 sekunder. LCP är också relativt långsam, särskilt på mobil där den når 4,2 sekunder, vilket innebär att stora visuella element tar tid att ladda in. Datorversionen är dock snabbare med 1,1 sekunder. När det gäller CLS presterar ASOS ganska bra med 0,024 på mobil och 0,014 på dator. Prestandapoängen för ASOS är något högre än Zalando på både mobil och dator, men lägre än Amazon, vilket visar att det finns utrymme för förbättringar.

Analys
-----------------------


Amazon är tydligt ledande i prestanda och användarupplevelse, särskilt på dator där laddningstiderna är exceptionellt låga. FCP på 0,6 sekunder och TBT på endast 80 ms gör den snabb och smidig för användaren. Även mobilversionen presterar starkt, med bättre resultat än konkurrenterna i flera kategorier, inklusive Speed Index och LCP. Webbsidan använder lågkvalitativa bilder och optimerade element, vilket minskar laddningstiderna och bidrar till den höga prestandapoängen. Samtidigt kan de lågkvalitativa bilderna påverka användarupplevelsen negativt, eftersom vissa användare kan koppla dålig bildkvalitet till oseriösa webbsidor eller bedrägerier. Den effektiva layouten hjälper dock till att stärka Amazons position som den snabbaste och mest användarvänliga sidan.

Zalando, däremot, har stora prestanda problem, särskilt för mobilversionen. Långa laddningstider och höga värden för Speed Index och LCP innebär att sidan är långsam och mindre användarvänlig. En bidragande faktor till detta är användningen av högkvalitativa bilder, som kan ge en mer visuellt tilltalande upplevelse men som också sänker ned prestandan och förlänger laddningstiderna. Datorversionen är något bättre med ett godkänt FCP, men fortfarande sämre än både ASOS och Amazon i flera mätvärden.

ASOS hamnar mellan Amazon och Zalando i prestanda. FCP är bra på både dator och mobil, men TBT är betydligt högre än hos konkurrenterna, vilket försämrar laddningstiden. Speed Index och LCP är godkända men inte lika bra som Amazons. ASOS använder sig också av högkvalitativa bilder, men till skillnad från Zalando lyckas sidan balansera detta med bättre optimering, vilket gör att den behåller en relativt bra prestanda. Sammanfattningsvis är ASOS bättre optimerad än Zalando men når inte samma nivå som Amazon.

För en bra användarupplevelse krävs en balans mellan hög prestanda och visuellt tilltalande bilder. Bilder av hög kvalitet kan förbättra designen, men de får inte påverka sidans laddningstid negativt. En väloptimerad sida ska också ha en bra struktur, där alla element är effektivt organiserade och inte försämrar prestandan.

Referenser
-----------------------

Övrigt
-----------------------

Emran Dzanic

[Amazon]: https://www.amazon.se/
[ASOS]: https://www.asos.com/se/
[Zalando]: https://www.zalando.se/