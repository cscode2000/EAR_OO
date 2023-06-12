# EAR_OO
Steuererkl�rung mit Einnahme-�berschussrechnung in Open Office/Libre Office
- klein, schnell und �bersichtlich f�r den t�glichen Gebrauch kleinerer Gewerbe
- ohne �berfl�ssigen Ballast
- l�uft unter allen Open Office Versionen (ab 1.1) und Libre Office
- l�uft mit allen Betriebssystem-Versionen, ohne externe Abh�ngigkeiten
- durch Zugriff auf Quellcode selbst anpa�bar
- Import vorhandener Daten einfach m�glich (z.B. Hibiscus Banking)
- erstellt auf Klick Umsatzsteuer-Voranmeldungen zum Import in Elster und Hibiscus...
- ... im Monat Dezember automatisch incl. Sonder-Vorauszahlung
- einfaches Erstellen der Anlage E�R und AVE�R
- Anzeige der relevanten Daten zur �bernahme in Umsatz-, Einkommen- und Gewerbesteuererkl�rung
- schnelles Sortieren der Buchungen nach allen Kriterien
- Kontenrahmen auf SKR04-Basis

Voraussetzung zur Nutzung ist eine vorhandene Installation von Open Office oder Libre Office.
Download hier: https://www.openoffice.org/download bzw. https://de.libreoffice.org/download

Zur Erh�hung des Komforts bei der Buchungseingabe werden Makros genutzt. Diese m�ssen daher erlaubt werden (Extras/Optionen/Sicherheit...). Die Datei sollte in ein Verzeichnis kopiert werden, in welchem Makros erlaubt sind. Die Dateiendung ggf. in "ods" �ndern und in diesem Format speichern. (*)

Bedienung:
- Im Blatt "Buch" werden beginnend in Spalte A die Buchungen eingegeben.
- Datum eingeben (z.B. 15.2.) Das Jahr wird nach Dr�cken von "Enter" automatisch passend erg�nzt.
- Weiterhin �ffnet sich nach "Enter" die Liste der Konten.
- mit Cursor oder Maus ausw�hlen, Klick oder Enter zum �bernehmen
- Eingabe der Kontonummer oder Bezeichnung grenzt die Liste ein
- um die Kontonummer manuell einzugeben, das Fenster mit Escape schlie�en
- Buchungstext und Steuersatz werden automatisch ausgef�llt, k�nnen aber �berschrieben werden
- Belegnummer wird automatisch hochgez�hlt
  - Prefix "AR" = Ausgangsrechnung, "ER" = Eingangsrechnung, "GT" = Geldtransfer
- die Felder Datum und Belegnummer k�nnen mit +/- hoch-/runtergez�hlt werden
- Betrag eingeben, nach "Enter" im Feld "Privateinlage" wird die n�chste Zeile begonnen
- betrifft die Kontonr. ein Anlagen-Konto, wird automatisch das Anlageverzeichnis (Blatt "Anlagen") erg�nzt. 
  - Nutzungsdauer und ggf. Abschreibungsbetrag manuell eintragen

Sonstiges:
- Um im E�R-Formular die Einlagen (Zeile 126) zu berechnen, eine 1 in Spalte "Privateinlage" eintragen, wenn es sich um eine Einlage handelt, z.B. eine Ausgangsrechnung von privat bezahlt wurde.
- Im Blatt "Konten" in F28 den Prozentsatz der Privatfahren von Kfz2 eintragen, falls dieser mittels Fahrtenbuch ermittelt wurde.
  - Kfz1 wird zu 100% betrieblich genutzt oder nach 1%-Regelung versteuert.
- Im Blatt "Steuererkl." den Hebesatz der Gemeinde eintragen, um die Gewerbesteuer zu berechnen.
- Beim UStVA-Export wird der Monat verwendet, wo sich der Cursor befindet.
- F�r den Transfer zu Hibiscus und Elster mu� das Makro EAR_UStVA angepa�t werden. (pers�nliche Daten, Dateipfade)
- Nicht ben�tigte Konten k�nnen ausgeblendet werden, um die Liste �bersichtlicher zu machen. (Rechtsklick auf Zeilennummer)
- Das Blatt ESt dient dazu, Kapitalertr�ge mehrerer Banken zu addieren und weitere Daten griffbereit zu haben.
- F�r den komfortablen Jahreswechsel mu� der Dokumentenname das Jahr in dieser Form enthalten: "EAR2023".

Es handelt sich um eine f�r eigene Zwecke erstellte Anwendung, die nur wenig f�r Einsatz durch andere modifiziert wurde, daher mit reduziertem Kontenrahmen, ohne Zellschutz, schicke Konfigurationsdialoge o.�. Gerne helfe ich bei individueller Anpassung.
(*) Makros und Dialoge sind zur Vereinfachung im Tabellendokument integriert. Selbst habe ich alles in eine eigene Bibliothek ausgelagert. Zur Kompatibilit�t mit Open Office 1.x liegt die Datei als ".sxc" vor, was von allen Office-Versionen gelesen werden kann.
-
https://github.com/cscode2000/EAR_OO
