# Netzwerk-Nationalteams
Ursprung und Datenerhebung
Der Datensatz bzw. die verschiedenen Kader der Nationalmannschaften wurde unter transfermarkt.de erhoben. Die Daten sind nach der Erhebung nicht anonymisiert worden. 
Es handelt sich um neun ungerichtete Gesamtnetzwerke der Nationalmannschaften Deutschland (DFB), Spanien (RFEF) und Frankreich (FFF).

EDGE-Attribute
id
(eindeutige Codierung des Knoten)
codiert von 1 bis 23, jede ID entspricht einem Spieler
weight
Beziehungsstärke durch die Dauer des Zusammenspiels der Akteure in einem Verein
3 = Die Akteure haben drei oder mehr Jahre miteinander gespielt.
2 = Die Akteure haben mehr als eine und weniger als drei Saisons miteinander gespielt.
1 = Die Akteure haben weniger als eine Saison miteinander gespielt.
0/n.a. =  Die Akteure haben nie miteinander im Verein gespielt.
relation Aktualität der Beziehung der Akteure zueinander:
no = Sie spielen momentan nicht im selben Verein .
yes =  Sie spielen aktuell miteinander im Verein.
NODE-Attribute
id
Identische ID wie aus der edgelist zur Identifikation der Knoten. In diesem Fall sind die Daten die Rückennummern der Spieler während des Turniers (1 bis maximal 23). 
Name
Name: Spielername (Nachname)

Club
Club: Aktueller Verein 

Vereinskürzel in 3 Zeichen (Bsp. VfB Stuttgart= VfB, Borussia Dortmund=BVB)


age
Aktuelles Alter zum Beginn des Turnierstarts:
1 = bis 20 Jahre
2 = 21 bis 23 Jahre
3 = 23 bis 25 Jahre
4 = 26 bis 29 Jahre
5 = 30 Jahre und älter
Value
Bedeutung des Spielers für den Erfolg der Nationalmannschaft 

Berechnet durch die Einsätze des Spielers geteilt durch die Gesamtanzahl der Spiele des jeweiligen Teams während der WM. 
