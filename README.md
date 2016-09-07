# Editor
Opdracht

Editor
Een tekstverwerker laat toe een tekst op te bouwen en aan te passen. Daarvoor
bestaan commando’s zoals cut, paste, copy, search-replace,. . . Voor deze
opgave zullen jullie ´e´en commando implementeren: de globale vervanging
van een woord dat een aantal keer herhaald werd, door ´e´en keer dat woord.
Opgave
Je krijgt een tekst bestaande uit een aantal lijnen, en daarna een aantal
commando’s die elk ´e´en keer op die tekst worden uitgevoerd, in de volgorde
waarin ze gegeven zijn. Een commando bestaat uit een getal N en een woord
W: elke rij van N opeenvolgende woorden W (gescheiden door een blanco)
in de gegeven tekst moet vervangen worden door juist ´e´en keer W, en dat
in heel de tekst.
Je programma geeft als output de resulterende tekst.
Het uitvoeren van het commando N W betekent meer precies: van in het
begin van de tekst, vervang het eerste voorkomen van N keer W door ´e´en keer
W, en zoek dan verder in de tekst naar een volgende voorkomen van N keer
W, enzovoort.
In de tekst wordt een woord W voorafgegaan door ´e´en blanco (behalve het
eerste woord van een lijn) en gevolgd door ´e´en blanco (behalve het laatste
woord van een lijn), en bevat zelf geen blanco’s.
De tekst bevat geen leestekens.
Invoer
De invoer bestaat uit een lijn met ´e´en getal T dat aangeeft hoeveel testen
er zijn, gevolgd door voor elke test (dus T keer):
 een lijn met ´e´en getal L dat aangeeft hoeveel lijnen de tekst heeft die
nu volgt
 L lijnen met tekst afgesloten door een new-line
 een lijn met ´e´en getal C dat aangeeft hoeveel commando’s volgen
 C commando’s van de vorm hieronder gespecifi¨eerd
Beschrijving van de commando’s
Elk commando bestaat uit ´e´en getal en ´e´en woord (waarin geen blanco’s
voorkomen). Bijvoorbeeld:
1
3 is
De bedoeling is dat dit commando elke opeenvolging van 3 keer is vervangt
door ´e´en keer is en dat van van links naar rechts in elke lijn van de
gegeven tekst.
Uitvoer
De uitvoer bestaat per test uit de tekst die verkregen wordt door alle commando’s
van die test toe te passen op de tekst gegeven voor die test, zonder
extra lijnen ertussen.
Voorbeeld
Invoer
2
2
ik heb heb een foutfout gemaakt
en en dat is is is niet goed
4
2 is
3 en
2 heb
2 fout
1
dit is een lange lange lange lange lijn met weinig duplicaten duplicaten
3
2 lange
2 duplicaten
3 lange
Uitvoer
ik heb een foutfout gemaakt
en en dat is is niet goed
dit is een lange lange lijn met weinig duplicaten
