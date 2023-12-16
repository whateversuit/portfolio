---
Title: Load
Template: analysis
---

Laddningstider
==========================
Uppgiften går ut på att mäta webbplatser användarvänlighet och laddningstid. 

Urval
-----------------------
Mätningarna kommer göras på sidorna som användes i föregående uppgift. Omni.se, reddit.com och youtube.com.


Metod
-----------------------
Google Sheets användes för att samla och dokumentera uppmätt data. DevTools nätverksflik i Chrome användes för att mäta laddningstider och PageSpeed Insights användes för att mäta prestandan hos sidorna.


Resultat
-----------------------

<img class ="omni-analysis" src="../image/omni.png" alt="">

Testerna på omni.se visar ett medel på 5 sekunder laddningstid. Storleken på sidan som laddades in var 4.45MB och performance för desktop-sidan var 71 och mobil visade 16. Antal requests var 290.

<img class ="reddit-analysis" src="../image/reddit.png" alt="">

Testerna på reddit.com visar ett medel på ungefär 6 sekunder laddningstid. Storleken på sidan som laddades in var 7.98MB och performance för desktop-sidan var 64 och mobil visade 41. Antal requests var 234.

<img class ="youtube-analysis" src="../image/youtube.png" alt="">

Testerna på reddit.com visar ett medel på ungefär 1 sekund laddningstid. Storleken på sidan som laddades in var 16.48MB och performance för desktop-sidan var 42 och mobil visade 33. Antal requests var 196.
Se nedan tabell för detaljerade mätningar.


<iframe class="sheet-container" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRJzWhpGUxzIxenRvecurDTOd__fUZtFG1CL3WBIfa8Yp247FBvuto_DJ39FilpSEqplc6hyBl_2H4T/pubhtml?widget=true&amp;headers=false"></iframe>
Tabell 1: Visar mätningar gjorda.




Analys
-----------------------
Resultatet visade att sidorna presterar olika i mätningarna. Enligt analysen har youtube den snabbaste laddningen. En anledning kan vara att sidan ej behöver ladda in annonser och banners eftersom att annonserna kommer i videos. Både omni och reddit har annonser som laddas in på huvudsidan. Högst prestanda för desktop hade omni med sina 71 följt av reddit på 64 och youtube på 42. På mobilprestanda hade reddit högst på sina 41 följt av youtube på 33 och omni på 16. 

Rangordning:
1. Youtube - Youtube vinner hastighetstestet och hamnar i mitten av performance. Youtube presterar alltid bra på både mobil och desktop vilket är imponerande med tanke på hur oändligt mycket inehåll sidan har. 

2. Reddit - Reddit fungerar bra och dugligt på både mobil och desktop. Medelhastigheten är något högre än youtube så där finns det förbättringspotential. Sidan skulle kunna priortera att ladda in inehållet före annonser och banners. Det har hänt ibland att bara reklamen laddar medans inehållet laddas trögt. Stor förbättringspotential här.

3. Omni - På tredje plats landar omni. Anledningen till att den är sist är för dess mediokra mobil-performance. 

Förslag till förbättringar:

Minska bildstorlekar och ladda in inehållet före annonser då alla dessa tre är ganska annonstunga. Reducera och optimera javascript-kod.

Mitt personliga gränsvärde ligger någonstans runt 2-3 sekunder. Det är nästan ett "krav" att sidorna i alla fall hinner visa något innehåll innan den tiden. Detta är viktigt för att användaren inte direkt ska klicka sig ur. Laddas bara annonser in har vi ett problem. 
Alla sidor uppfyller mitt krav även om både reddit och omni har 5 sekunder. Inehåll laddas in i olika takt här vilket gör att det fungerar. Upplevelsen blir OK till bra på dessa sidor. 

Referenser
-----------------------
<a href="https://omni.se">omni.se</a><br>
<a href="https://reddit.com">reddit.com</a><br>
<a href="https://youtube.com">youtube.com</a><br>
<a href="https://pagespeed.web.dev/">PageSpeed Insights</a><br>




Övrigt
-----------------------
Av Emil Lindström 2023.