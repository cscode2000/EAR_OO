# EAR_OO
Einnahme-Überschussrechnung in Open Office/Libre Office
- klein, schnell und übersichtlich für den täglichen Gebrauch kleinerer Gewerbe
- ohne überflüssigen Ballast
- läuft unter allen Open Office Versionen (ab 1.1) und Libre Office
- läuft mit allen Betriebssystem-Versionen, ohne externe Abhängigkeiten
- durch Zugriff auf Quellcode selbst anpaßbar
- Import vorhandener Daten einfach möglich (z.B. Hibiscus Banking)
- erstellt auf Klick Umsatzsteuer-Voranmeldungen zum Import in Elster und Hibiscus...
- ... im Monat Dezember automatisch incl. Sonder-Vorauszahlung
- Anzeige der relevanten Daten zur Übernahme in Umsatz-, Einkommen- und Gewerbsteuererklärung
- schnelles Sortieren der Buchungen nach allen Kriterien
- Kontenrahmen auf SKR04-Basis

Voraussetzung zur Nutzung ist eine vorhandene Installation von Open Office oder Libre Office.
Download hier: https://www.openoffice.org/download bzw. https://de.libreoffice.org/download

Zur Erhöhung des Komforts bei der Buchungseingabe werden Makros genutzt. Die Datei sollte daher in ein Verzeichnis kopiert werden, in welchem Makros erlaubt sind (Extras/Optionen/Sicherheit...). Die Dateiendung ggf. in "ods" ändern und in diesem Format speichern. (*)

Bedienung:
- Datum eingeben (z.B. 5.2. - das Jahr wird automatisch ergänzt)
- nach Drücken von "Enter" öffnet sich die Liste der Konten
- Eingabe der Kontonummer oder Bezeichnung grenzt die Liste ein
- mit Cursor oder Maus auswählen, Klick oder Enter zum Übernehmen
- Buchungstext und Steuersatz werden automatisch ausgefüllt, können aber überschrieben werden
- Belegnummer wird automatisch hochgezählt, Prefix "AR" = Ausgangsrechnung, "ER" = Eingangsrechnung, "GT" = Geldtransfer
- die Felder Datum und Belegnummer können mit +/- hoch-/runtergezählt werden
- Betrag ausfüllen, nach "Enter" im Feld "Privateinlage" wird die nächste Zeile begonnen

Sonstiges:
Um im EÜR-Formular die Einlagen (Ziffer 123) zu berechnen, eine 1 in Spalte "Privateinlage" eintragen, wenn es sich um eine Einlage handelt, z.B. eine Ausgangsrechnung von privat bezahlt wurde.
Im Blatt "Konten" in F28 den Prozentsatz der Privatfahren von Kfz2 eintragen, falls dieser mittels Fahrtenbuch ermittelt wurde.
Kfz1 wird zu 100% betrieblich genutzt oder nach 1%-Regelung versteuert.
Im Blatt "Steuererkl." den Hebesatz der Gemeinde eintragen, um die Gewerbesteuer zu berechnen.
Für den Transfer zu Hibiscus und Elster muß das Makro EAR_UStVA angepaßt werden. (persönliche Daten, Dateipfade)
Das Blatt ESt dient dazu, Kapitalerträge mehrerer Banken zu addieren und weitere Daten griffbereit zu haben.

Es handelt sich um eine für den eigene Zwecke erstellte Anwendung, die nur wenig für Einsatz durch andere modifiziert wurde, daher mit reduziertem Kontenrahmen, ohne Zellschutz, schicke Konfigurationsdialoge o.ä.

(*) Makros und Dialog sind zur Vereinfachung im Tabellendokument integriert. Selbst habe ich alles in eine eigene Bibliothek ausgelagert. Zur Kompatibilität mit Open Office 1.x liegt die Datei als ".sxc" vor, was von allen Office-Versionen gelesen werden kann.
