# Netzwerk-Nationalteams
# CODEBUCH							
											
## edgelist	## 
Grundregel: 	Die Edgelist darf pro Spalte immer nur einen Wert enthalten. Bis auf die ID idealerweise numerisch codiert (als Zahl).						

**from**	

definiert den ersten Spieler der Beziehung. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort						

**to**	 	

definiert den anderen Spieler in der Beziehung. Entspricht ID in der Nodelist. Keine Sonderzeichen, etc. 						

**weight**	

Anzahl der Saisons, die die beiden Spieler im selben Verein gespielt haben (Beziehungsstärke), definiert nach ganzen Zahlen.						
**relation**	

definiert, ob die beiden Spieler zum Zeitpunkt der Weltmeisterschaft im selben Verein spielen. Dichotome Ausprägung: yes/no						

## nodelist ##
Grundregel: 	die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen. Ausprägungen der Attribute in der Regel numerisch definieren.	


**id**		

eindeutige Identifikation jedes einzelnen Spielers (vertex), der erfasst wird. Nachname des Spielers, falls Dopplung, Anfangsbuchstabe Vorname 			dahinter 			

**number**	

Rückennummer des Spielers als kürzere, eindeutige Identifikation						

**club**	

Verein, bei dem der Spieler zum besagten Turnier spielt. Kürzel nach Legende						

**age**		

Alter nach Aufteilung in der Skala						

**value**	

Bedeutung des Spielers am Erfolg der Mannschaft, Anzahl Turnier-Einsätze/Anzahl Turnier-Spiele des Teams						
							
**NA**		

definiert fehlende Werte						
							
		
