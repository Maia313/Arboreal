# FirstWebpage
Arboreal

Bestående av 4 sidor, där jag har valt att ha Home and Themes på samma sida.
Webbplatsen har en column layout
Loggan används i header footer och på varje av de 4 sidorna
Jag använder genomgående samma typsnitt med variation i storlek beroende på textinnehållet.
Både HTML- och Css- koden är validerade. Jag har lagt till opacity på färger, jag använder även en polygon, vilket CSS validator klagar på(det har jag valt att bortse ifrån). 

Indenteringen ser kanske lite annorlunda ut här på Github därför är det bra att ladda ner koden som en zip-fil.







// Feedback från Angel

Farger ser ut okej, koden är väl skrivit men liten problem med strukturen på några delar.
Webbsidan fungerar bra och effekten på nav ser ut snygg. Contact och Pricing sidor ser ut
nästan perfekt med designen. 
Ner har jag skrivit detaljer om mina tankar och dem flesta är personlig skulle inte stämma
som en regel. 
#About
Kod:
L41: </p> skulle snyggare på samma nivå som den <p>
L46: </article> sama som L41
Om du skulle estrukturera bättre koden, det skulle vara liten lättare att läsa. Med dem 
items som går inne. exampel:
<header>
    <h1><img class="logo" src="blak.png" alt="Logo">RBOREAL - plants for the office environment </h1>
    <div class="slogan">
        <blockquote>
            <em>- A workplace that is alive creates ideas that live on.</em>
        </blockquote>
    </div>
</header>
Jag vet inte om det är min kodläsare eller om du har inte strukturerat koden på en lätt sätt
Annars koden ser ut som var bra skrivit. 
Design:
Vänster bilden ser ut som stör med den bakgrunden bilden. Den A bredvid "Who we are" ser ut
inte snygg.
På footer den A ensamma skulle vara bättre med hela arboreal ordet och nån "copyright" symbol
#Contact
Kod:
Koden ser ut ganska bra strukturerat, mycket bättre än ABOUT
Design:
Perfekt, just samma med den "A" bredvid Contact Us och på footer
#home
Kod:
L20: Skulle röra det ute en tab
L35: Skulle röra det inne 2 tab
L50: </p> ute också kanske
Design:
Vänster bilden ser ut som det stör på med bakgrunden bilden.
ust samma med den "A" bredvid Most popular themes och på footer
#Pricing
Kod:
L62 och L63 </div> skulle vara på samma nivå som dem i  L37 och L38 annnars all ser ut bra
DEsign:
Om du skulle komplettera tabel med priserna skulle se ut mer komplett, annars det ser ut
bra och ren.
samma med den "A" bredvid Contact Us och på footer
CSS:
Kanske det är personlig men jag skulle ordna items alfabetisk och skulle börja med taggar 
och sen med klasser. Men jag tror att det inte viktig.







// De synpunkter som har att göra med indenteringen har jag valt att bortse ifrån eftersom koden är korrekt indenterad. Jag har       upptäckt att indenteringen ändras i olika kodläsare.

De kommentarer som berör design har jag läst, dock har valt att inte ändra någonnting eftersom det anges inga bra motiveringar till varför det skulle vara bra att göra några ändringar.

Har också valt att inte strukturera min CSS-kod i alfabetisk ordning eftersom jag tycker att detta är ingen bra ide.


Det finns dock några ändringar som jag har gjort. Dessa är följande:

+ Har ökat färgkontrasten på min sida, genom att ta bort opacity på vissa färger och öka intensiteten på de andra. Detta pga jag tycker att när skärmen blir mindre så är det bättre när kontrasten ökas.
+ Har gjort sidan responsiv genom att lägga till breakpoints för 1060px, och 600px. Dessa valdes eftersom texten hamnar annars konstigt i tillhörande flexboxar.

*Du uppfyller alla krav från Individuell examination 1. // Ja

*Du har implementerat egna media queries så att din hemsida anpassar sig för mobil, tablet samt desktop. // Ja

*Du väljer själv vilka breakpoints du använder dig utav. I din README.md som ska ligga i projektet ska du motivera valet av breakpoints, vad var det som gjorde att du valde precis det värdet för att ändra strukturen på sidan?  // Har motiverat-se ovan

*Du beskriver också vilket responsivt mönster du har utgått ifrån och varför det var ett bra val för sidan. This is responsive: patterns. // Mönstret som jag använder är Column drop, eftersom desktop versionen är strukturerat i columner.

*Du har förbättrat din hemsida utifrån den feedback du fick från föregående inlämning samt skrivit ner vad du har ändrat för att möta denna feedback alternativt motiverat varför du inte har ändrat utefter återkopplingen du fick. Denna reflektion skrivs ner i din README.md. // Se ovan






