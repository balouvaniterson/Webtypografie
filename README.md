 Web typografie / Balou van Iterson / VID-1

<h1>Web Typografie</h1>
Dit is mijn repository voor web-typografie. In deze repository vind je mijn versie van de fragmenten van de film <i>Blade Runner 2049</i>. Hieronder meer info.

<h1>Het kunstwerk</h1>
<img src="https://designarchives.aiga.org/assets/images/000/100/717/100717_lg.jpg">
<p>Het kunstwerk dat ik heb uitgekozen is een poster van <em>The Denver Centre Theatre Company</em>. Een Tony award winnend theater bedrijf.</p>
<p>De poster hoort bij een serie van soortgelijke posters voor hun 2009-2010 theaterseizoen. Zo hoort iedere poster bij zijn eigen theatervoorstelling en bestaat deze uit 2 delen. Op het eerste deel staat de naam van de voorstelling groot samen met een bijpassende afbeelding. Op het andere deel staat een groot bijbehorend stukje text.</p>
<p>De poster die ik hebt uitgekozen hoort bij de theatervoorstelling genaamd: <em>Mama hated diesels</em>. Op het eerste deel zie je een truck met muzieknoten en de naam. Op het 2de deel zie je een stuk text namelijk: "How can you carry a payload if you can't carry a tune." Hiermee wil het theaterbedrijf een eerste indruk geven over het verhaal van de voorstelling.</p>
<p>De stijl van de poster is erg minimalistisch. Ze hebben simpele vormen gebruikt en weinig details toegevoegd. Ook hebben ze maar 3 kleuren gebruikt op de gehele poster. <br /> Omdat de poster uit 2 delen bestaat, heb ik dit ook verwerkt in mijn kunstwerk.</p>
<p>Hier kun je het kunstwerk nogmaals zien op de website. <br /> <a href="https://designarchives.aiga.org/#/entries/Denver%20Center%20Theatre%20Company/_/detail/relevance/asc/0/7/21027/denver-center-theatre-company-2009-10-season-poster-series/2">Poster</a></p>

<h1> Concept </h1>

Het idee achter mijn kunstwerk is dat ik beide posters wou verwerken in één kunstwerk. Daarnaast heb ik alleen de elementen overgenomen die ik belangrijk vond. Zoals de titel, afbeelding en natuurlijk de kleuren.

Ik heb gekozen om het kunstwerk in landscape te maken. Ik vond het belangrijk om de truck groot te centreren, aangezien ik wou dat dit het middelpunt van mijn kunstwerk werd. Ook had ik al snel het idee om de truck de animeren. Zodat het lijkt alsof hij rijdt en het kunstwerk echt tot leven komt.

<h2> Poster vertalen naar kunstwerk </h2> 
Om de poster te vertalen naar het kunstwerk. Ben ik in Adobe Illustrator begonnen met het namaken van de poster. Na dat hij klaar was. Heb ik alle individuele elementen gegroepeerd en deze in verschillende layers geplaatst. Zo worden ze ook automatisch gegroepeerd wanneer je hem in html plakt.

<br>

<img src="https://i.ibb.co/qmL5jCm/Screenshot-2020-05-25-at-14-52-57.png">

Nadat ze waren gelayerd, heb ik het bestand als svg geexporteerd en deze in de html geplakt. 

Toen kon er worden begonnen aan de html/css/js.

<h1>HTML/CSS</h1>

<h2> SVG </h2>

Om de individuele elementen te stylen. Heb ik de paths van de svg's classes of id's gegeven. Zodat ik deze in de css kon oproepen en hiervan bijvoorbeeld de "fill"(kleur) kon veranderen. 

<img src="https://i.ibb.co/7ydWb5n/Screenshot-2020-05-25-at-15-02-39.png">

Ik heb ook sommige groepen van paths een class gegeven. Zo dat ik de hele groep kon stylen i.p.v. per individueel path.

<h2> Interactie </h2>

Om het kunstwerk nog meer tot leven te laten komen heb ik een aantal functies gebruikt om hem interactief te maken.

<h3> Hover </h3>

Zo heb ik gebruik gemaakt van hovers op een aantal elementen. Zo heeft de tekst bijvoorbeeld een hover. Wanneer de gebruiker over de tekst hovered veranderd deze van kleur. Dit heb ik gedaan met een fill. Om dit iets uit te breiden heb ik bij de tekst rechtsboven, een soort <i>easter egg</i> toegevoegd. Zo heeft de tekst als groep een hover, en het child hiervan dus bijvoorbeeld 3 letters van het woord ook nog een hover met een ease. Als je dit bij ieder woord rechtsboven doet komen de woorden: <b>I AM TED</b> naar voren. Ted is de trucker.

<img src="https://i.ibb.co/hycMXDv/Screenshot-2020-05-25-at-15-16-20.png">

<h3> Animaties </h3>

Zo heb ik een aantal animaties gebruikt. Sommige van internet en sommige zelf gemaakt. Zo heb ik bijvoorbeeld de auto laten rijden, de rook laten verschijnen, de koplampen laten knipperen, de noten laten bewegen. 
Dit heb ik gedaan met @keyframes. Zo heb ik door middel van transforms de svg's laten kunnen verplaatsen en bewegen, fill's om de kleuren te laten veranderen en opactity om elementen te laten verdwijnen.

Om de animaties idle meteen te laten beginnen heb ik een class aangemaakt bij een element in de html en deze class name gebruikt voor de keyframes. 

<img src="https://i.ibb.co/6WT6Jkg/Screenshot-2020-05-25-at-15-29-58.png">

Om de animaties iets meer aan te passen heb ik deze nog los neergezet in de css. Waardoor ik ze een duration kon geven. Of ik ik kon stellen hoe vaak die zich achter elkaar moet herhalen. Of om bijvoorbeeld een delay te geven voordat de animatie begint.

<h2> Javascript </h2>

Ik heb gebruik gemaakt van JS om door middel van keyboardtoetsen, elementen te laten veranderen.
Zo heb ik a.d.h.v. keyframes classes gemaakt. Om vervolgens in JS een functie te schrijven die deze class bovenop een andere class aan een element toe te voegen. Zo kun je bijvoorbeeld de achtergrond kleur veranderen door op een toets te klikken. 

<img src="https://i.ibb.co/DRm0XRD/Screenshot-2020-05-25-at-15-40-31.png">

Eerst heb ik een var aangemaakt van de body.
Daarna een eventlistener om door middel van een toets een class te togglen.
Daarna een functie aangemaakt, wanneer je op een specifieke toets klikt, er een class bovenop de andere class wordt geplaatst.

Ik heb 4 verschillende toetsen gebruikt voor 4 verschillende "thema's".

<img src="https://i.ibb.co/MNSXXZ2/Screenshot-2020-05-25-at-15-41-02.png">

De thema's zijn: 
- Blauw thema (b)
- Geel thema (g)
- Donkere thema (spatie)
- Party thema (p)

<img src="https://i.ibb.co/209CbPX/Screenshot-2020-05-25-at-15-42-24.png">

Je kunt ook verschillende thema's over elkaar zetten voor een specialer effect.

<h2> Responsive </h2>

Ik heb het kunstwerk responsive gemaakt voor mobiel door middel van:
meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes"

<br>

Daarnaast heb ik in css de afbeelding verplaastst en de achtergrond vergroot.
<img src="https://i.imgur.com/yt3xAJa.png">

<h2> Extra </h2>

Als extra heb ik nog een cursor van een Amerikaanse vlag toegevoegd, deze veranderd wanneer je klikt.
Dit heb ik gedaan met de cursor property, daarnaast heb ik er ook een op body:active gezet zodat deze verschijnt wanneer je klikt.

<img src="http://icons.iconarchive.com/icons/iconfactory/copland-6/32/American-Flag-icon.png">
<img src="http://icons.iconarchive.com/icons/iconfactory/copland-6/32/American-Flag-2-icon.png"">

<h2> Bronnen </h2>

- https://css-tricks.com/almanac/
- https://animista.net/
