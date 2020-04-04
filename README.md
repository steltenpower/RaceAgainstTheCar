# RaceAgainstTheCar
_your browser can translate the following Dutch_
(fka ParkerenOfDemarreren)<br>
Met een paar seconden fietsen inschatten of je sneller bent dan een auto op een bepaalde A-naar-B

Parkeren Of demarreren?
Over realistische reistijd en graag willen winnen.
===============================================================================

Bij het gespreksonderwerp reistijd (wat ik vaak startte geinspireerd door de fantastische artikelen van 
onderzoeksjournalist Thalia Verkade) hoor ik mensen (al dan niet geholpen door reisplanners) vaak 
dingen beweren die nogal afwijken van mijn eigen ervaring op dezelfde A-naar-B met fiets danwel auto. 
Nadenkend waar dat aan kan liggen kwam ik o.a. op:

[1] Overschatten effect topsnelheid op reistijd:
================================================
Ik hoor meermaals een schatting lijkend op "afstand gedeeld door 140 plus een handjevol minuten". Je 
auto overdrijft z'n snelheid echter iets (dat bespaart bekeuringen), maar vooral dat eerste en laatste stukje 
waar je vaak maar 30 mag, of 50 met stoplichten, neemt doorgaans veel meer dan een handjevol minuten.
Ga eens de deur-tot-deur tijd meten (pas op: sommige fietscomputers meten alleen de tijd dat je rijdt)

[2] Onderschatten/vergeten vertraging door standaard drukte (vooral bij auto's):
================================================================================
Eerder genoemde schatting gaat uit van nauwelijks ander verkeer en dat is zeldzaam. De meeste mensen willen namelijk rijden als de meeste mensen willen rijden. Dan haal je zeker in de auto maar weinig de maximaal toegestane 
snelheid. En met veel haast houdt je te weinig afstand tot je voorganger, moet je regelmatig remmen, dat 
zeker met appende bestuurders snel tot files lijdt. En dan hebben we het nog niet eens over afritten, 
kruispunten, etc. Fietsers hebben hier overigens minder last van, die staan niet stil in een file, maar 
rijden er langs en hoeven ook bijna nooit te wachten op 'de volgende groen', kunnen eventueel met 
afstappen doorgaans gewoon door bij opbrekingen of een stukje afsnijden door voetgangersgebied.
Sommige planners schatten tegenwoordig de reistijd in adhv hoe lang anderen daar eerder over deden op 
hopelijk vergelijkbare momenten. Maar dan moet je wel daadwerkelijk die begin- of eindtijd instellen ...

[3] Onderschatten snelheid fietser:
===================================
e-bikes, pedelecs en ook zonder trapondersteuning gaan moderne fietsen een stuk sneller dan die van een 
halve eeuw geleden. Vroeger was de vuistregel dat een 'gewone' fiets ongeveer 15 km/u gaat, maar 25 is 
het nieuwe 15. Dat levert ook extra risico's, die grotendeels zijn op te lossen door er aan te wennen 
en door infrastructuur er voldoende op aan te passen. We fietsen namelijk niet alleen overdag bij windstil weer zonder bagage of passagier op droge kaarsrechte brede fietssnelwegen (die overigens ongeveer net zo breed zijn als slechts 1 rijbaan op een autosnelweg). Zo is dat hobbeltje dat bij 15 flink oncomfortabel is, bij 25 al snel gevaarlijk, want zelfs even vergetend dat e-bikes ook nog zwaarder zijn kom je al op bijna 3 maal de bewegingsenergie

[4] Vergeten deel reis, plus effectieve reistijd:
=================================================
Dingen als tanken, banden oppompen, reparatie, en het terugverdienen van de all-in kosten van onze heilige koe en/of stalen ros, heeft Thalia al uitvoerig behandeld in https://decorrespondent.nl/8416/waarom-de-fiets-veel-sneller-is-dan-je-denkt-en-de-auto-veel-trager/884917783200-095bef5c. De tijd om te parkeren (zoeken, manouvreren, betalen, wandelen) bij A en B wil ik hier echter nogmaals noemen, omdat die iedere rit van toepassing is. Ook als B slechts een overstappunt is naar een volgende vervoersmodus naar C. Dan is het bijvoorbeeld misschien wel veel makkelijker om met je vouwfiets zo het perron op te fietsen (ik bedoel natuurlijk wandelen met de fiets aan de hand :-) )

Bovenstaande stukje tekst zal autogebruik weinig verminderen, tenzij ...
========================================================================
Wat mogelijke richtingen:
- Alan Smith (toen werkend voor Office for National Statistics) zei in een presentatie over 
datavisualisatie, informatie dicht bij mensen te brengen. Geef ze niet alleen de landelijke gemiddeldes, 
maar ook de waarden over hun eigen buurt, of nog beter: laat ze die eerst raden, want een concreet gemaakt verschil met de werkelijkheid helpt het leerproces.
- Vaak gaat onze menselijke informatieverwerking slechts via ogen en hersenen. Maar hoe meer je van je 
lichaam inzet, hoe beter het binnenkomt en blijft hangen.
- Verandering en interactie houdt de aandacht er langer bij.
- Veel mensen willen graag winnen. Maak er een spelletje van

Even op de pedalen; idee voor een wedstrijdje:
==========================================================
Bovenstaande analyse inspireerde tot het volgend functioneel ontwerp in grote lijnen:
Al fietsend, echt of wat veiliger op een hometrainer, voortdurend op je smartphone/scherm zien hoe je huidige snelheid zich vertaalt in reistijd. En hoe die zich verhoudt tot die van een auto met meenemen van zo veel mogelijk doorgaans vergeten factoren: Middels isochronen (contouren van gelijke reistijd), die in het geval van de fiets meeveranderen met de huidige snelheid. Liefst aangevuld met een meebewegende groene markering over het deel van de kaart waarvoor je het wint van de auto.

Aannames bij berekening:
========================
De tijd benodigd om je fiets te parkeren is heel laag in NL, want fietsenstalling is dichtbij en/of op stoep mag en kan doorgaans worden geparkeerd. Het opladen van een e-bike doe je doorgaans bijna gratis in je schuurtje thuis terwijl je slaapt. Beiden opgeteld strepen we deze weg tegen de tijd die een automobilist gemiddeld kwijt is aan parkeerplaats zoeken, plus ook nog tanken (incl. eventueel omrijden, betalen, etc.). We negeren dan ook nog tijd voor aanschaf, onderhoud/reparatie, administratie om nog maar niet te spreken over de tijd die je nodig hebt om alle kosten terug te verdienen. Menigeen blijkt een dag in de week voor de auto te werken. Een preciezere berekening kan je nalezen in ... van Thalia Verkade en aanpassen naar je eigen situatie.<br>

Implementatie, help je mee?:
============================
Een kaartje vergelijkbaar met dat op https://medium.com/@Urbica.co/hello-galton-e6e07a7164b7#effa waarvoor je dus de snelheid door te trappen varieert, of gewoon met een schuifje. En dan met hometrainer (heb een Tacx) on tour langs verschillende grote werknemers om mensen aan het fietsen te zetten. Help je het mee realiseren? Programmeren en geo-dingen zijn ondanks wat ervaring, namelijk geen dagelijkse routine voor me. Input is welkom via "issues" hier op https://github.com/steltenpower/ParkerenOfDemarreren , waar naast deze tekst ook een schets van de beoogde gebruikersinterface (.html bestand) en daarvan een (doorgaans wat achterlopend) screenshot (.png bestand).


Wat nou, als de fiets het (nog) niet wint?:
===========================================
Wint thuiswerken, of de fiets het voor jou nog niet van de auto voor deze bestemming?<br>
En als je het nou combineert met de trein, zoals miljoenen andere treinfietsers in Nederland doen? ...<br>
En als ook jouw werkgever danwel woonplaats erachter komt dat al die autoparkeerplaatsen veel te duur zijn voor hen en dus flink duurder en verder weg gaan worden voor automobilisten (lees ... )<br>

Of als je niet fietsen wilt?
============================
Als je denkt mij krijgen ze toch niet uit de auto heb ik ook nog een tip: De snelste en goedkoopste manier om door te kunnen rijden is niet meer asfalt voor auto's, maar minder auto's: dus stimuleer anderen (o.a. via je politieke stem) om te gaan fietsen.

Low-tech alternatief, dat veel breder ingezet kan worden:
=========================================================
Een print optie aanbieden en vervolgens iedere eigenaar van een gebouw waar veel mensen (nog) met de auto komen aanschrijven om die te printen op of A0 (liefst gratis via sponsoring) aan te vragen om vervolgens op tactische plek(ken) op te hangen en ook de link breed door te sturen (met het verzoek eventuele missende fietsdoorsteekjes toe te voegen op openstreetmap.org )

maybe useful: https://www.omnicalculator.com/ecology/car-vs-bike
