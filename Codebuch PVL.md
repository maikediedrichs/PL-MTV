<h1> PVL: Netzwerkanalyse Allianz MTV Stuttgart - Codebuch </h1>

<b> Edgelist: </b> <br>
from <br>
definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort<br>
to 	<br>
definiert den Empfänger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, etc. <br>

Nodelist:
id	eindeutige Identifikation jedes einzelnen Knotens
name	Name oder Bezeichnung des Knotens. 
type	definiert die Art des Knotens, 0 = Person, 1 = Organisation (Verein, Heimatland)
birth	definiert das Geburtsjahr der Person
age	definiert das Alter der Person, skaliert: 0 = unter 21, 1 = 21-23, 2 = 24-26, 3 = 27-30, 4 = über 30
position	definiert die Spielposition auf dem Feld, 1 = Mittelblock, 2 = Zuspiel, 3 = Außenangriff, 4 = Diagonal, 5 = Libero
country	definiert das Heimatland des Knotens, 1 = Deutschland, 2 = Niederlande, 3 = Belgien, 4 = Bulgarien, 5 = Polen, 6 = Finnland, 7 = USA, 8 = Spanien
stuttgart	definiert, seit wann die Spielerinnen bei Allianz MTV Stuttgart spielen
