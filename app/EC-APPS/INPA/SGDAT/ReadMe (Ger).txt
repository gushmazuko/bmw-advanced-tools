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
  
Sollte auf ihrem Rechner INPA in dem Verzeichnis C:\EC-APPS\INPA installiert
sein, so m�ssen Sie noch den Inhalt des Verzeichnis C:\INPA nach C:\EC-APPS\INPA
verschieben.

Nachdem dies durchgef�hrt wurde befinden sich alle notwendigen 
Dateien in den entsprechenden Verzeichnissen. 

Zum Starten des TD-53x INPA Skripts mu� eine Verkn�pfung zu 
"C:\INPA\BIN\INPALOAD.EXE" erstellt werden und als Parameter in 
den Eigenschaften der Verkn�pfung "TD-530.IPO" �bergeben werden. 
Mit Hilfe dieser Verkn�pfung kann dann das INPA Skript immer 
gestartet werden. Wollen Sie die englische Version des Skriptes
starten so m�ssen sie als Parameter "TD-530_ENG.IPO" angeben.


2. Arbeiten mit dem TD-53x INPA Skript
--------------------------------------

Hier einige Hinweise zum Arbeiten mit dem TD-53x INPA Skript

CheckIn:
Beim Durchf�hren eines kompletten CheckIn werden s�mtliche Daten eines Fahrzeuges
festgehalten, die zu Beginn der Analyse an einem Fahrzeug ben�tigt werden.

CheckOut:
Beim Ausf�hren eines kompletten CheckOut wird das Fahrzeug unabh�ngig von den
zuvor durchgef�hrten Arbeiten wieder in einen Zustand gebracht in dem es gefahren
werden kann.

Trace:
Mit der Trace Funktionen k�nnen Aufzeichnungen von mehreren beliebigen Steuerger�te-Gr��en
gemacht werden. �ber die Datei "TRACE.TST" wird festgelegt, aus welchen Steuerger�ten welche
Parameter ausgelesen werden sollen. Diese Datei hat den gleichen Aufbau wie eine EDIABAS
Testdatei. Die Werte werden zyklisch ausgelesenen und in einer Ergebnisdatei abgelegt. 

Ergebnisdatei:
Beim Ausf�hren aller Aufgaben bzw. Jobs werden die Fahrzeugdaten immer in einer
Ergebnisdatei im Verzeichnis "C:\FAHRZEUG.DAT" abgespeichert. Der Name der Ergebnis-
datei setzt sich aus der Fahrgestellnummer und der durchgf�hrten Aufgabe zusammen.
Der Name der Ergebnisdatei wird immer in der Kopfzeile des Fensters angezeigt.

Daten sichern:
Das TD-53x INPA Skript bietet die M�glichkeit, s�mtliche Daten, die von einem Fahrzeug 
ausgelesen wurden und sich im Verzeichnis "C:\FAHRZEUG.DAT" befinden, zentral auf einem 
Serverlaufwerk zu speichern. Die dazu notwendige Funktionen k�nnen �ber den Men�punkt
"F9" des Hauptmen�s aufgerufen werden. Die f�r die Sicherung der Daten notwendigen
Einstellungen k�nnen �ber die Dateien "TD-530.INI" (Konfiguration des Men�s), bzw. 
"TD-530.BAT" (Konfiguration der Sicherungs Verzeichnisse) gemacht werden.

Individuelle Einstellungen:
In der Datei TD-530.cfg ist es m�glich, individuelle Einstellungen vorzunehmen. N�here 
Informationen zu den einzelnen Einstellungen finden Sie in der Datei selbst. 


3. Probleme
-----------

Sollten Probleme beim Arbeiten mit dem TD-53x INPA Skript auftreten, so k�nnen Sie mir
durch folgende Vorgehensweise bei der Fehlerbeseitigung helfen:
- In der Datei "TD-530.CFG" unter der Rubrik "Parameter" den Parameter "Logging" auf "ON"
  stellen.
- Problem mit INPA Skript nachstellen.
- Die Dateien "TD-530.LOG" aus dem Verzeichnis "C:\FAHRZEUG.DAT" 
  zusammen mit der dazugeh�renden Fehlerbeschreibung an mich senden.
  
  
4. Ansprechpartner
------------------

Autor     : G�nter Stra�er
Abteilung : TD-531
Telefon   : 08731/7629182
Handy     : 0179/4747804
Email     : guenter.strasser@bmw.de