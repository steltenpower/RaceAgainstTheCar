# ParkerenOfDemarreren
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
auto overdrijft z'n snelheid echter iets (dat bespaart bekeuringen) en dat eerste en laatste stukje 
waar je vaak maar 30 mag, of 50 met stoplichten neemt veel meer dan een handjevol minuten.
Ga eens de deur-tot-deur tijd meten (pas op: sommige fietscomputers meten alleen de tijd dat je rijdt)

[2] Onderschatten/vergeten vertraging door standaard drukte (vooral bij auto's):
================================================================================
Bovenstaand is als er nauwelijks ander verkeer is en dat is zeldzaam. De meeste mensen willen namelijk rijden als de meeste mensen willen rijden. Dan haal je zeker in de auto maar weinig de maximaal toegestane 
snelheid. En met veel haast houdt je te weinig afstand tot je voorganger, moet je regelmatig remmen, dat 
zeker met appende bestuurders snel tot files lijdt. En dan hebben we het nog niet eens over afritten, 
kruispunten, etc. Fietsers hebben hier overigens minder last van, die staan niet stil in een file, maar 
rijden er langs en hoeven ook bijna nooit te wachten op 'de volgende groen', kunnen eventueel met 
afstappen doorgaans gewoon door bij opbrekingen of een stukje afsnijden door voetgangersgebied.
Sommige planners schatten tegenwoordig de reistijd in adhv hoe lang anderen daar eerder over deden op 
hopelijk vergelijkbare momenten. Maar het gespreksonderwerp is meestal op een rustiger moment dan het 
daadwerkelijk rijden ...

[3] Onderschatten snelheid fietser:
===================================
e-bikes, pedelecs en ook zonder trapondersteuning gaan moderne fietsen een stuk sneller dan die van een 
halve eeuw geleden. Vroeger was de vuistregel dat een 'gewone' fiets ongeveer 15 km/u gaat, maar 25 is 
het nieuwe 15. Dat levert ook extra risico's, die grotendeels zijn op te lossen door er aan te wennen 
en door infrastructuur er op aan te passen (We fietsen niet alleen overdag bij windstil weer op droge 
kaarsrechte brede fietssnelwegen zonder bagage of passagier. Dat hobbeltje dat bij 15 flink oncomfortabel is, wordt bij 25 al snel gevaarlijk, want bijna 3 maal de bewegingsenergie)

[4] Vergeten deel reis, plus effectieve reistijd:
=================================================
Dingen als tanken, banden oppompen, reparatie, en het terugverdienen van de all-in kosten van onze heilige koe en/of stalen ros, heeft Thalia al uitvoerig behandeld in https://decorrespondent.nl/8416/waarom-de-fiets-veel-sneller-is-dan-je-denkt-en-de-auto-veel-trager/884917783200-095bef5c. De tijd om te parkeren (zoeken, manouvreren, betalen, wandelen) bij A en B wil ik hier nog extra noemen, omdat die iedere rit van toepassing is. Ook als B slechts een overstappunt is naar een volgende vervoersmodus naar C. Dan is het bijvoorbeeld misschien wel veel makkelijker om met je vouwfiets zo het perron op te fietsen (ik bedoel natuurlijk wandelen met de fiets aan de hand :-) )

Bovenstaande stukje tekst zal autogebruik weinig verminderen, tenzij ...
========================================================================
Wat mogelijke richtingen:
- Alan Smith (toen werkend voor Office for National Statistics) zei in een presentatie over 
datavisualisatie informatie dicht bij mensen te brengen. Geef ze niet alleen de landelijke gemiddeldes, 
maar ook de waarden over hun eigen buurt, of nog beter: laat ze die eerst raden, want een concreet gemaakt verschil helpt het leerproces.
- Vaak gaat onze menselijke informatieverwerking slechts via ogen en hersenen. Maar hoe meer je van je 
lichaam inzet, hoe beter het binnenkomt en blijft hangen.
- Verandering en interactie houdt de aandacht er langer bij.
- Veel mensen willen graag winnen. Maak er een spelletje van

Even op de pedalen, een idee voor een ingedikte wedstrijd:
==========================================================
Bovenstaande analyse inspireerde tot het volgend functioneel ontwerp in grote lijnen:
Al fietsend, echt of wat veiliger op een hometrainer, voortdurend op je smartphone/scherm zien hoe je huidige snelheid zich vertaald in reistijd en hoe die zich verhoudt tot die van een auto met meenemen van zo veel mogelijk doorgaans vergeten factoren: Middels isochronen [contouren die rond een middelpunt alle punten van gelijke reistijd verbinden] voor de fiets die meeveranderen met de snelheid en dan een groene waas leggen over het deel van de kaart waarvoor je het wint van de auto.

Implementatie, help je mee?:
============================
Een dashboard met wat default parameters die je kunt aanpassen, met daarnaast een kaart die wat lijkt op die op https://medium.com/@Urbica.co/hello-galton-e6e07a7164b7#effa en waarop je locaties kunt aangeven waar mee gerekend wordt. En dan zo'n hometrainer on tour langs verschillende grote werknemers om mensen aan het fietsen te zetten. Help je het mee realiseren? Programmeren en geo-dingen zijn ondanks wat ervaring, namelijk geen dagelijkse routine voor me. Input is welkom op https://github.com/steltenpower/ParkerenOfDemarreren , waar ik naast deze tekst binnenkort wat schetsen van de beoogde gebruikersinterface en code zal neerzetten.

Ruud Steltenpool
