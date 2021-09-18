TD-53x INPA Skript
------------------

1. Installation
---------------

Bitte gehen Sie zur Installation des TD-53x Skripts folgenderma�en
vor:
- �ffnen Sie das Installations Archiv mit Winzip
- W�hlen Sie den Men�punkt extrahieren
- Geben Sie beim Extrahieren folgende Optionen an
  * Extrahieren nach		: "C:\"
  * Dateien �berschreiben 	: Ja
  * Pfadangaben verwenden	: Ja
  
Nachdem dies durchgef�hrt wurde befinden sich alle notwendigen 
Dateien in den entsprechenden Verzeichnissen.

Zum Starten des TD-53x INPA Skripts mu� eine Verkn�pfung zu 
"C:\INPA\BIN\INPALOAD.EXE" erstellt werden und als Parameter
"TD-530.IPO" �bergeben werden. Mit Hilfe dieser Verkn�pfung kann
dann das INPA Skript immer gestartet werden.


2. Arbeiten mit dem TD-53x INPA Skript
--------------------------------------

Hier einige Hinweise zum Arbeiten mit dem TD-53x INPA Skript

CheckIn:
Beim Durchf�hren eines kompletten CheckIn werden s�mtliche Daten eines Fahrzeuges
festgehalten, die zum Beginn der Analyse an einem Fahrzeug ben�tigt werden.

CheckOut:
Beim Ausf�hren eines kompletten CheckOut wird das Fahrzeug unabh�ngig von den
zuvor durchgef�hrten Arbeiten wieder in einen Zustand gebracht in dem es gefahren
werden kann.

Trace:
Mit der Trace Funktionen k�nnen Aufzeichnungen von mehreren beliebigen Steuerger�te Gr��en
gemacht werden. �ber die Datei "TRACE.TST" wird festgelegt aus welchen Steuerger�te welche
Parameter ausgelesen werden sollen. Diese Datei hat den gleichen Aufbau wie eine EDIABAS
Testdatei. Die Werte werden zyklisch ausgelesenen und in einer Ergebnisdatei abgelegt. 

Ergebnisdatei:
Beim Ausf�hren aller Aufgaben bzw. Jobs werden die Fahrzeugdaten immer in einer
Ergebnisdatei im Verzeichnis "C:\FAHRZEUG.DAT" abgespeichert. Der Name der Ergebnis-
datei setzt sich aus der Fahrgestellnummer und der durchgf�hrten Aufgabe zusammen.
Der Name der Ergebnisdatei wird immer in der Kopfzeile des Fensters angezeigt.


3. Ansprechpartner
------------------

Autor     : G�nter Stra�er
Abteilung : TD-532
Telefon   : 08731/7629182
Handy     : 0179/4747804
Email     : guenter.strasser@bmw.de