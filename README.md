<p>Web typografie / Balou van Iterson / VID-1</p>
<h1>Web Typografie</h1>
<p><br />Dit is mijn repository voor web-typografie.</p>
<p>In deze repository vind je mijn versie van de fragmenten van de film Blade Runner 2049.</p>
<h2>De opdracht</h2>
<p>De opdracht was om aan de hand HTML/CSS/JS een closed-captions ontwerp te maken voor Darice. Darice is laat doof, hierdoor is het lastig om een film echt te beleven. Closed captions helpen om de film beter te begrijpen, maar de echte film beleving is nog ver te zoeken. Met mijn ontwerp hoop ik in ieder geval een stapje vooruit te zetten richting een goede beleving.&nbsp;</p>
<h2>&nbsp;</h2>
<h2>Voorbereiding</h2>
<p>Omdat we speciaal voor Darice moesten onwerpen, mochten er vragen aan haar worden gesteld. Ik heb deze vragen naderhand geanalyseerd en aan de hand hiervan heb ik een persona van haar kunnen maken.</p>
<p><img src="/darice.jpg" alt="Persona Darice" width="1080" height="720" /></p>
<p>Tijdens het ontwerpen van de closed-captions, kon ik deze er dan af en toe naast houden. Om te kijken of ik nog wel voor Darice aan het ontwerpen was.</p>
<p><img src="/dariceclosed.png" alt="Closed Darice" /></p>
<p>Om mij zelf beter te kunnen verdiepen in de fragmenten heb ik de film gekeken en geanalasyeerd.&nbsp;</p>
<h2>&nbsp;</h2>
<h2>Font</h2>
<p>Ik heb voor <em>"Brenner font"&nbsp;</em>gekozen. Aangezien deze veel verschillende stijlen heeft en ik deze verschillende dan kon gebruiken voor de verschillende personages. Zo werd het sneller duidelijk wie er sprak en gaf zo'n ander lettertype een bepaalde sfeer mee, die bij het karakter pastte.</p>
<h2>&nbsp;</h2>
<h2>Concept</h2>
<p>Mijn idee was om aan de hand van de gezichten van de personages en de tekst van de personages, het verhaal heel duidelijk te laten overkomen. Zo cre&euml;er je veel duideijkheid over wie er aan het woord is. Zelfs wanneer er meerdere personen tegelijk praten. Ook krijg je een bepaalde sfeer mee door middel van het gezicht en de tekstopmaak. Ook heb ik gekeken naar de positie van de gezichten en tekst. Zo heb ik de positie gebaseerd op waar de stem vandaan kwam in het fragment.&nbsp;</p>
<p>Daarnaast wou ik ook de atmosferische geluiden overbrengen. Dit heb ik gedaan door effecten toe te voegen aan de video. Zo heb ik bijvoorbeeld het beeld laten trillen wanneer er een vaartuig opsteeg. Of de kleuren van de video laten veranderen wanneer de hoofdpersoon zich ontdaan voelt.</p>
<p>Door deze combinatie wou ik de ervaring van in dit geval Darice verbeteren, zodat zij met meer plezier een film kan kijken.</p>
<h2>&nbsp;</h2>
<h2>Versie 1</h2>
<p>In versie 1 heb ik vooral gepuzzeld met de teksten. Zo heb ik alle personages "tags" meegegeven. Deze tags kwamen aan het beginnen van iedere zin. In de tag stond de naam van het karakter. Ik heb ieder karakter ook een andere kleur meegegeven. Zo werd het snel duidelijk wie aan het praten was. Ook heb ik verschillende lettertypes meegegeven aan de karakters.</p>
<p><img src="/tag.png" alt="tag" /></p>
<p>Feedback versie 1:</p>
<p>- Een tag alleen de eerste keer dat dat personage spreekt laten zien.</p>
<p>- Tekst wit houden.</p>
<p>- "Fuck off, Skinhead" in caps.&nbsp;</p>
<p>- Visueel experiment doen.</p>
<p>&nbsp;</p>
<h2>Versie 2</h2>
<p>In versie 2 ben ik gaan experimenteren met de gezichten. Ik heb in Illustrator alle gezichten nagemaakt en gelayered. Het gezicht van de examinator was niet te zien, daarom heb ik geen details toegevoegd aan dit gezicht. Ik heb de gezichten daarna geexporteerd als svg en deze in de code toegevoegd. Daarna heb ik ieder onderdeel een id gegeven en deze in css een kleur gegeven. Zo kon ik de svg's nog aanpassen als ik dat wou. Vervolgens heb ik de sounds file enorm veel sounds aangemaakt. Zodat ik de svg's perfect kon timen met de video. (Achteraf was dit enorm veel werk en helemaal niet handig). Zo moest ik ze dus steeds apart stijlen per sound. En kon ik ze met de opacity laten verschijnen en verdwijnen.&nbsp;</p>
<p><img src="/joekarakter.png" alt="karakter" /></p>
<p>Het gaf een cool effect, het probleem was alleen dat ik nu de sounds niet meer kon gebruiken voor effecten.&nbsp;</p>
<p>Feedback versie 2:</p>
<p>- De svg's omvormen tot een background-img zodat ik deze kon toevoegen aan de p's. (aan de hand van ::before of ::after's.)</p>
<p>- Geluiden toevoegen.</p>
<p>- Plek van de karakters baseren op geluid.</p>
<p>&nbsp;</p>
<h2>Versie 3</h2>
<p>In versie 3 heb ik het systeem omgegooid. Aangezien ik die geluiden toch echt wel graag wou toevoegen. Dit heeft heel wat uurtjes gekost, gelukkig heb ik veel hulp kunnen krijgen van Chelsea. (Nogmaals bedankt!) Zo heb ik van de svg's, jpg's gemaakt en deze aan de hand van ::before's kunnen toevoegen aan de teksten.&nbsp;</p>
<p><img src="/robotcode.png" alt="robot" /></p>
<p>Nu kon ik effecten toevoegen aan de video. Aan de hand van keyframes kon ik deze effecten in css maken en op de sounds toevoegen aan de video. Deze heb ik allemaal gefinetuned, en ieder geluid en passend effect gegeven.</p>
<p><img src="/shakecode.png" alt="effect" /></p>
<p>Effecten die ik heb toegevoegd zijn:&nbsp;</p>
<ul>
<li>Het scherm laten trillen wanneer er een voertuig opstijgt.</li>
<li>De video inverted maken wanneer de personage zich ontdaan voelt.</li>
<li>Het scherm langzaam laten inzoomen wanneer er een langdurige piep is.</li>
<li>De achtergrond langzaam van kleur laten veranderen wanneer er een langdurige piep is.</li>
<li>Het scherm in laten zoomen wanneer er een alarm af gaat.</li>
<li>Het scherm rood laten kleuren wanneer er een alarm af gaat.</li>
<li>Het scherm wit laten kleuren wanneer er een bepaald alarm af gaat.</li>
</ul>
