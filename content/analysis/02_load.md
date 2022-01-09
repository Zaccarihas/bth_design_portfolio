---
Title: Report - Load
Description: Analysis report regarding loading time
Template: analysis
---

Analys av laddtider och effektivisering
=======================================

Uppgiften bestod i att analysera effektivitet och prestanda för tre utvalda siter. Tre sidor på respektive utvald site skulle analyseras och resultaten skulle analyseras och sammanställas till en rekommendation på förbättringsmöjligheter för respektive site.

Siterna skulle också jämföras och placeras i en lista där den site som presterat bäst skulle hamna på första plats och den site som presterade sämst skulle placeras sist i listan.

Urval
-----------------------

För den här uppgiften valde jag att göra en lokal jämförelse av olika aktörer i min hem kommun Örnsköldsvik. Jag ville se hur olika verksamhetsområden 
hanterade prestandan på sina sidor. Jag ville dock att aktörerna skulle vara någorlunda jämförbara i storlek och i IT-resurser så jag valde en stark förening (Modo Hockey), kommunen (Örnsköldsviks kommun) och en av de större kommersiella aktörerna (Metsä Board).

* [Modo Hockey](https://www.modohockey.se/)
* [Örnsköldsviks kommun](https://www.ornskoldsvik.se/)
* [Metsä board](https://www.metsaboard.com/Pages/default.aspx)


Metod
-----------------------

Jag mätte varje sida via [PageSpeed Insight](https://pagespeed.web.dev/) och analyserade resultatet och de förslag som sidan ger på förbättringar.

Nedladdningen av varje sida mätte jag också via Chromes Dev Tools (Network) och noterade resultaten i en sammanställning.

*Resultatsammanställning*
<iframe class="calcsheet" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vR-PDqzYCN8P9Bm-ik3Q4Rt-qJ0CRj8oQCfJaxNiZ0X2Ez7u6vk4cSM914Gog2Z9lW5b2-A6-s67jw1/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe>


Avslutningsvis gick jag igenom och jämförde resultaten för att försöka förstå inom vilket område som respektive sida kunde förbättras.


Resultat
-----------------------

### Modo Hockey
![Modo hockeys hemsida](%base_url%/image/modo.png)
*Framsida - Modo hockey*

Eftersom några av sidorna som man kan navigera till i Modos-meny inte ligger på samma domän så exkluderade jag dessa och valde därför ut följande sidor för min analys:

* [Framsida](www.modohockey.se)
* [Mat och dryck](https://www.modohockey.se/mat-dryck)
* [Medlemssida](https://www.modohockey.se/om-modo-hockey/medlem)

#### Framsidan
![Prestanda indikation för Modo hockeys mobila framsida](%base_url%/image/insight_modo_1_m_kpi1.png)
*Prestanda indikering, mobila enheter*

![Prestanda indikation för Modo hockeys desktop framsida](%base_url%/image/insight_modo_1_c_kpi1.png)
*Prestanda indikering, desktop*

#### Mat och dryck

![Prestanda indikation för Modo hockeys mobila mat- och drycksida](%base_url%/image/insight_modo_2_m_kpi1.png)
*Prestanda indikering, mobila enheter*

![Prestanda indikation för Modo hockeys desktop mat- och drycksida](%base_url%/image/insight_modo_2_c_kpi1.png)
*Prestanda indikering, desktop*

#### Medlemssidan

![Prestanda indikation för Modo hockeys mobila medlemssida](%base_url%/image/insight_modo_3_m_kpi1.png)
*Prestanda indikering, mobila enheter*

![Prestanda indikation för Modo hockeys desktop medlemssida](%base_url%/image/insight_modo_3_c_kpi1.png)
*Prestanda indikering, desktop*

### Örnsköldsviks kommun
![Örsnsköldsviks kommuns hemsida](%base_url%/image/ovikskommun.png)
*Framsida - Örnsköldsviks kommun*

Från Örnsköldsviks kommuns hemsida valde jag följande sidor:

* [Framsida](https://www.ornskoldsvik.se/)
* [Fritidstipset](https://www.ornskoldsvik.se/marknad/fritidstipset/fritidstipset)
* [Företag och näringsliv](https://www.ornskoldsvik.se/marknad/foretag-och-naringsliv/foretag-och-naringsliv)

#### Framsidan
![Prestanda indikation för Örnsköldsviks kommuns mobila framsida](%base_url%/image/insight_ovik_1_m_kpi1.png)
*Prestanda indikering, mobila enheter*

![Prestanda indikation för Örnsköldsviks kommuns desktopframsida](%base_url%/image/insight_ovik_1_c_kpi1.png)
*Prestanda indikering, desktop*

#### Fritidstipset
![Prestanda indikation för Örnsköldsviks kommuns mobila fritidstipssida](%base_url%/image/insight_ovik_2_m_kpi1.png)
*Prestanda indikering, mobila enheter*

![Prestanda indikation för Örnsköldsviks kommuns desktop fritidstipssidaframsida](%base_url%/image/insight_ovik_2_c_kpi1.png)
*Prestanda indikering, desktop*

#### Företag och näringsliv
![Prestanda indikation för Örnsköldsviks kommuns mobila näringslivssida](%base_url%/image/insight_ovik_3_m_kpi1.png)
*Prestanda indikering, mobila enheter*

![Prestanda indikation för Örnsköldsviks kommuns desktop näringssida](%base_url%/image/insight_ovik_3_c_kpi1.png)
*Prestanda indikering, desktop*

### Metsä board
![Metsä Boards hemsida](%base_url%/image/metsa.png)
*Framsida - Metsä Board*

För Metsä Board valde jag att analysera följande sidor:

* [Framsida](https://www.metsaboard.com/)
* [About us](https://www.metsaboard.com/About-Us/)
* [Metsä Board Magazine](https://www.metsaboard.com/Media/Pages/default.aspx#Mets-Board--Magazine)

#### Framsida

![Prestanda indikation för Metsä Boards mobila framsida](%base_url%/image/insight_metsa_1_m_kpi1.png)
*Prestanda indikering, mobila enheter*

![Prestanda indikation för Metsä Boards desktopframsida](%base_url%/image/insight_metsa_1_c_kpi1.png)
*Prestanda indikering, desktop*

#### About Us

![Prestanda indikation för Metsä Boards mobila About Us sida](%base_url%/image/insight_metsa_2_m_kpi1.png)
*Prestanda indikering, mobila enheter*

![Prestanda indikation för Metsä Boards desktop About Us sida](%base_url%/image/insight_metsa_2_c_kpi1.png)
*Prestanda indikering, desktop*

#### Metsä Board Magazine

![Prestanda indikation för Metsä Boards mobila magazinesida](%base_url%/image/insight_metsa_3_m_kpi1.png)
*Prestanda indikering, mobila enheter*

![Prestanda indikation för Metsä Boards desktop magazinesida](%base_url%/image/insight_metsa_3_c_kpi1.png)
*Prestanda indikering, desktop*

Analys
-----------------------
Vid min analys så satte jag ett gränsvärde på 2 sek för sidan att laddas, vilket jag uppfattar som en rimlig tid att invänta en websida av den aktuella storleken över en normal bredbandsuppkoppling.

### Mobila plattformar nedprioriterade

Gemensamt för alla tre siter som jag har testat är att de ger bättre prestanda i sina desktop-versioner, vilket sannolikt betyder att de inte har lagt lika mycket vikt eller resurser på att utveckla de mobila plattformarna.

Jag skapade ett jämförelsevärde där jag jämförde sidornas mobila prestandavärde med motsvarande desktopvärde, och både Örnsköldsviks kommun och Modo Hockey hade ungefär hälften så bra mobilprestanda som desktopprestanda. Sämst var dock Metsä Board som inte ens kom upp i en fjärdedel så bra prestanda på sina mobila sidor.

### Bilder

Gemensamt för alla siter och både för mobila enheter och desktop, så verkar det vara bilder som orsakar de största prestandaproblemen.
De rekommendationer som lämnas av Insight Page Speed är att sidorna bör använda sig av modernare bildformat, att bilder bör vara i rätt storlek och att bilderna ska kodas effektivt. Metsäboard hade också problemet att de för sin Magzine sida läste in bilder som sedan inte visade på sidan. Här rekommenderas istället att man skjuter upp inläsningen till dess bilderna visas sk "Lazy Loading".

Med modernare bildformat och med bättre anpassade bilder så tror jat att prestandan skulle öka markant på samtliga siter.
Mängden bilder skilde sig ganska mycket mellan siterna, och speciellt Modo Hockey skulle förmodligen kunna se över behovet av vissa av deras bilder och kanske försöka hitta bättre alternativ så som svg-ikoner istället.

### Oanvända JavaScript

Framförallt Modo Hockey men även Metsä Board hade problem med att onödiga JavaScript laddades ner till sidorna.

Förmodligen används stora tredjepartsscripts som t ex jquery på dessa siter. Om sidorna distribuerar dessa själva så skulle en möjlig prestandahöjandeåtgärd vara att använda sig av bättre caching-rutiner eller kanske framförallt att använda sig av en Common Distribution Network (CDN). 

### Servertider

Alla siter fick också anmärkning på resurser som blockerade renderingen av sidorna och för Modo Hockey men framförallt för Metsä Board rekommenderades att se över serverns initiala svarstid. 

Metsä Board verkar generera sina sidor från en underliggande databasserver och det är möjligt att det skulle kunna vinna tid på att se över servern så att den har rätt mjukvara men även tillräckligt med minne för att kunna processa sidorna. 

Den här bristen är dock marginell i jämförelse med de vinster som skulle göras om man skulle se över bildproblemen.

### Rankinglista och vinnare
Kampen om första plats var jämn mellan Örnsköldsviks kommun och Metsä Board när det gäller nedladdningstider i jämförelse med den total storleken på innehållet, men där ändå Örnsköldsviks kommun segrade med relativt god marginal.

Örnsköldsviks kommun tyckte jag dessutom hade en smartare struktur på sidorna, där innehållet verkar ha delats upp på fler undersidor, vilket i sin tur  har gett färre resurser per sida och kortare nedladdningstider. 

Örnsköldsviks kommun får också pluspoäng för den genomtänkta tillgänglighetsmenyn som presenteras på deras framsida, även om detta inte direkt är relevant för sidans prestanda.

Min topplista blir därför:
1. Örnsköldsviks kommun
2. Metsä Board
3. Modo Hockey

Övrigt
-----------------------

Mitt namn är Anders Löfqvist och jag genomförde denna analys som en enskild uppgift.