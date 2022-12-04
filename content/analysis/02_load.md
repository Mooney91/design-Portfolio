Utvärdering av webbplatsers laddningstid och användbarhet
=======================

Den här rapporten analyserar och utvärderar laddningstiden av några webbplatser. Data kommer att samlas in och analyseras och webbplatserna kommer att rangordnas. Rekommendationer kommer sedan att ges för att visa hur webbplatsens laddningstid kan förbättras. 

Urval
-----------------------

Följande tre e-handelswebbplatser har valts ut för analys: 

* [Amazon](https://www.amazon.co.uk/) 

![Amazon](%assets_url%/img/amazon.jpg) 

Amazon är bland annat ett multinationellt e-handelsföretag som har en stor marknadsandel i Storbritannien. Det är världens största e-handelsföretag. 

* [Argos Limited](https://www.argos.co.uk/) 

![Argos](%assets_url%/img/argos.jpg) 

Argos är en “catalogue retailer” som finns i Storbritannien och Irland. De säljer allmänna varor genom fysiska butiker och online. 

* [John Lewis & Partners](https://www.johnlewis.com/) 

![John Lewis](%assets_url%/img/johnlewis.jpg) 

John Lewis & Partners, en del av den medarbetarägda ömsesidiga organisationen känd som John Lewis Partnership - det största kooperativet i Storbritannien, äger och kör exklusiva varuhus som finns i hela Storbritannien. Företaget säljer allmänna varor. 

Eftersom de alla kommer från samma industrin med liknande mål kan en mer rättvis jämförelse genomföras. Som brittiska webbplatser fokuserar de också på en viss marknad. Som Anstey et all. (2020) diskuterar finns det några exemplen där laddningstid har påverkat vissa företagsförsäljningar. Vid en så viktig tidpunkt av det kommersiella året skulle det vara klokt att analysera dessa tre webbplatser. 

Metod
-----------------------

Två huvudverktyg har använts i denna rapport. Den första är Google Pagespeed. Tre webbplatser har mätts med detta verktyg, tre gånger, för både mobil och dator. 

Det andra verktyget är Devtools i Mozilla Firefox. Nätverksfliken visar laddningstiden samt antalet och storleken på de resurser som används på webbplatsen. Återigen kommer varje webbplats att mätas tre gånger. 

Om en webbplats har mätts flera gånger kommer ett slutligt medelvärde att beräknas som kommer att användas som grund för jämförelsen med andra webbsidor. 

Resultat
-----------------------

I tabellerna nedan (som visas i Excel-kalkylbladet) visas resultaten och rådata från analysen i sin helhet: 

<iframe width="100%" height="500" frameborder="0" scrolling="no" src="https://studentbth-my.sharepoint.com/personal/zamo22_student_bth_se/_layouts/15/Doc.aspx?sourcedoc={ddaed643-77e2-4e9b-a030-551d27b82144}&action=embedview&wdAllowInteractivity=False&Item='Results'!A5%3AL27&wdHideGridlines=True&wdDownloadButton=True&wdInConfigurator=True&wdInConfigurator=True&edesNext=true&edrtees6=false&resen=false"></iframe>

Amazon uppnådde det högsta PageSpeed betyget med c.97 medan John lewis den lägsta för Desktop-enheter. Alla webbplatser uppnådde sämre resultat för mobila enheter. Det är särskilt sant för John Lewis som hade 33 för betyget medan de andra hade 72 (Amazon) och 53 (Argos). 

För laddningstid var Amazon snabbast med 0.781s medan John Lewis tog 3.317. Amazon laddade det största antalet resurser, men totalt var en mindre storlek jämfört med de andra webbplatserna. John hade färre resurser att ladda, men detta var mycket svårt att mäta. Resurser fortsatte att laddas även efter en minut efter den första laddningen. Det var väldigt likt med Argos, men totalen (efter en minut) var mycket lägre. 

Analys
-----------------------

Amazon var tydligt "vinnaren" i alla delar av testen. Amazon uppnådde det högsta PageSpeed-resultatet för desktoppar och mobiler. Dessutom var laddningstiden mycket snabbare trots att de hade ett större antal resurser. 

Argos var tvåa i vårt test med näst högsta resultat. Laddningstiden var också högre än John Lewis. 

För John Lewis uppnådde det lägsta resultatet, särskilt för mobila enheter. Laddningstiden var särskilt långsam och sidan fortsatte att laddas många filer även efter den första laddningen. 

Amazon är naturligtvis ett stort förtaget som har mycket resurser och expertis som de kan använda. Det var särskilt väldigt tidigt att utveckla deras webbplats och ehandel-infrastruktur Som en konsekvens har de antagligen mer erfarenhet att utveckla en effektiv webbplats som är inriktad på att attrahera kunder.  

John Lewis:s webbplats använder mycket JavaScript. Det är en anledning varför det är långsamt och det laddar upp kontinuerligt. En rekommendation är att använda ett verktyg såsom CSSNano och UglifyJS som kan förminska CSS och Javascript som används på webbplatsen (Moz 2022). Det är också troligt att det kan finnas något "render-blockerande" Javascript som används, vilket Moz (2022) inte heller rekommenderar. 

Argos använder många .gif filer. Eftersom är de inte animerad kunde webbplatsen konvertera dem till .jpeg eller .png och komprimera filerna för att minska storleken. Ändringar av bilder kan göras med en enkel bildredigeringsprogramvara. För icke-bild filer kan man använda ett verktyg som hette Gzip  (Moz 2022) som kan komprimera filerna (såsom HTML/CSS/Javascript) 

Alla tre webbplatserna är en acceptabel hastighet för mig för desktop enheter. Å andra sidan skulle hastigheten som John Lewis tog på mobila enheter vara mycket långsam, särskilt om man behöver kontinuerligt navigera mellan sidorna. När man vill handla någonting är det särskilt viktigt att jämföra olika produkter. Det är inte en bra upplevelse för kunder som måste vänta för webbplatsen att ladda ner. 

Sammanfattningsvis var Amazon den klara vinnaren. Alla tre webbplatserna måste arbeta med sin mobila upplevelse, särskilt nu när människor börjar använda mobiler mer. Det här är nästa utmaning nu när företagen konkurrerar om fler kunder. 

Referenser
-----------------------

Amazon.com, Inc. 2022. *Amazon.co.uk: Low Prices in Electronics, Books, Sports Equipment & More.*. https://www.amazon.co.uk/ (Hämtad 2022-12-03). 

Anstey, Chris; Pavic, Bojan och Wagner, Jeremy. 2020. *Why does speed matter?*. https://web.dev/why-speed-matters/ (Hämtad 2022-12-03). 

Argos Limited. 2022. *Argos Order online today*. https://www.argos.co.uk/ (Hämtad 2022-12-03). 

John Lewis & Partners. 2022. *John Lewis & Partners: Homeware, Fashion, Electricals & More*. https://www.johnlewis.com/. (Hämtad 2022-12-03). 

Moz.2022. *Page Speed*. https://moz.com/learn/seo/page-speed (Hämtad 2022-12-04). 

PageSpeed Insights. 2022. *PageSpeed Insights*. https://pagespeed.web.dev/ (Hämtad 2022.12-03). 

Övrigt
-----------------------

Zachary Mooney (författare)