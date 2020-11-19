# Netzwerk-Nationalteams
# CODEBUCH							
											
## edgelist ##					

**from**	

definiert den ersten Spieler der Beziehung. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort						

**to**	 	

definiert den anderen Spieler in der Beziehung. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort 						

**weight**	

Anzahl der Saisons, die die beiden Spieler im selben Verein gespielt haben (Beziehungsstärke), definiert nach ganzen Zahlen.	

**relation**	

definiert, ob die beiden Spieler zum Zeitpunkt der Weltmeisterschaft im selben Verein spielen. Dichotome Ausprägung: yes/no						

## nodelist ##

**id**		

eindeutige Identifikation jedes einzelnen Spielers (vertex), der erfasst wird. Nachname des Spielers, falls Dopplung, Anfangsbuchstabe Vorname dahinter 			

**number**	

Rückennummer des Spielers als kürzere, eindeutige Identifikation						

**club**	

Verein, bei dem der Spieler zum besagten Turnier spielt. Kürzel nach Legende						

**age**		

Alter in ganzen Zahlen angegeben.						

**value**	

Bedeutung des Spielers am Erfolg der Mannschaft, Anzahl Turnier-Einsätze des Spielers. Höchstens sind sieben Spiele möglich.						
							
**NA**		

definiert fehlende Werte						
							
## Legende zu den Vereinskürzeln ##

**Spanische La Liga**

ATH - Athletic Bilbao

ATM – Atletico Madrid

BAR – FC Barcelona

RMA – Real Madrid

SEV – FC Sevilla

VAL – FC Valencia

VIL – FC Villareal


**Englische Premier League**

ARS – FC Arsenal London

CHE – FC Chelsea

LIV – FC Liverpool 

MCI – Manchester City

MUN – Manchester United 

TOT – Tottenham Hotspur


**Deutsche Bundesliga**

BMG – Borussia Mönchengladbach

BVB – Borussia Dortmund

FCB – Bayern München

H96 – Hannover 96

S04 – Schalke 04

SCF – SC Freiburg

VFB – VfB Stuttgart


**Italienische Serie A**

JUV – Juventus Turin

LAZ – Lazio Rom

SAM – Sampdoria Genua


**Französische Ligue 1**

ASM – AS Monaco

OL – Olympique Lyon 

OM – Olympique Marseille

PSG – Paris Saint-Germain
