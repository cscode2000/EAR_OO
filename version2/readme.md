# EAR_OO
Steuererklärung mit Einnahme-Überschussrechnung in Open Office/Libre Office
- klein, schnell und übersichtlich für den täglichen Gebrauch kleinerer Gewerbe
- ohne überflüssigen Ballast
- läuft unter allen Open Office Versionen (ab 1.1) und Libre Office
- läuft mit allen Betriebssystem-Versionen, ohne externe Abhängigkeiten
- durch Zugriff auf Quellcode selbst anpaßbar
- Import vorhandener Daten einfach möglich (z.B. Hibiscus Banking)
- erstellt auf Klick Umsatzsteuer-Voranmeldungen zum Import in Elster und Hibiscus...
- ... im Monat Dezember automatisch incl. Sonder-Vorauszahlung
- einfaches Erstellen der Anlage EÜR und AVEÜR
- Anzeige der relevanten Daten zur Übernahme in Umsatz-, Einkommen- und Gewerbesteuererklärung
- schnelles Sortieren der Buchungen nach allen Kriterien
- Kontenrahmen auf SKR04-Basis

Voraussetzung zur Nutzung ist eine vorhandene Installation von Open Office oder Libre Office.
Download hier: https://www.openoffice.org/download bzw. https://de.libreoffice.org/download

Zur Erhöhung des Komforts bei der Buchungseingabe werden Makros genutzt. Diese müssen daher erlaubt werden (Extras/Optionen/Sicherheit...). Die Datei sollte in ein Verzeichnis kopiert werden, in welchem Makros erlaubt sind. Die Dateiendung ggf. in "ods" ändern und in diesem Format speichern. (*)

Bedienung:
- Im Blatt "Buch" werden beginnend in Spalte A die Buchungen eingegeben.
- Datum eingeben (z.B. 15.2.) Das Jahr wird nach Drücken von "Enter" automatisch passend ergänzt.
- Weiterhin öffnet sich nach "Enter" die Liste der Konten.
- mit Cursor oder Maus auswählen, Klick oder Enter zum Übernehmen
- Eingabe der Kontonummer oder Bezeichnung grenzt die Liste ein
- um die Kontonummer manuell einzugeben, das Fenster mit Escape schließen
- Buchungstext und Steuersatz werden automatisch ausgefüllt, können aber überschrieben werden
- Belegnummer wird automatisch hochgezählt
  - Prefix "AR" = Ausgangsrechnung, "ER" = Eingangsrechnung, "GT" = Geldtransfer
- die Felder Datum und Belegnummer können mit +/- hoch-/runtergezählt werden
- Betrag eingeben, nach "Enter" im Feld "Privateinlage" wird die nächste Zeile begonnen
- betrifft die Kontonr. ein Anlagen-Konto, wird automatisch das Anlageverzeichnis (Blatt "Anlagen") ergänzt. 
  - Nutzungsdauer und ggf. Abschreibungsbetrag manuell eintragen

Sonstiges:
- Um im EÜR-Formular die Einlagen (Zeile 126) zu berechnen, eine 1 in Spalte "Privateinlage" eintragen, wenn es sich um eine Einlage handelt, z.B. eine Ausgangsrechnung von privat bezahlt wurde.
- Im Blatt "Konten" in F28 den Prozentsatz der Privatfahren von Kfz2 eintragen, falls dieser mittels Fahrtenbuch ermittelt wurde.
  - Kfz1 wird zu 100% betrieblich genutzt oder nach 1%-Regelung versteuert.
- Im Blatt "Steuererkl." den Hebesatz der Gemeinde eintragen, um die Gewerbesteuer zu berechnen.
- Beim UStVA-Export wird der Monat verwendet, wo sich der Cursor befindet.
- Für den Transfer zu Hibiscus und Elster muß das Makro EAR_UStVA angepaßt werden. (persönliche Daten, Dateipfade)
- Nicht benötigte Konten können ausgeblendet werden, um die Liste übersichtlicher zu machen. (Rechtsklick auf Zeilennummer)
- Das Blatt ESt dient dazu, Kapitalerträge mehrerer Banken zu addieren und weitere Daten griffbereit zu haben.
- Für den komfortablen Jahreswechsel muß der Dokumentenname das Jahr in dieser Form enthalten: "EAR2023".

Es handelt sich um eine für eigene Zwecke erstellte Anwendung, die nur wenig für Einsatz durch andere modifiziert wurde, daher mit reduziertem Kontenrahmen, ohne Zellschutz, schicke Konfigurationsdialoge o.ä. Gerne helfe ich bei individueller Anpassung.
(*) Makros und Dialoge sind zur Vereinfachung im Tabellendokument integriert. Selbst habe ich alles in eine eigene Bibliothek ausgelagert. Zur Kompatibilität mit Open Office 1.x liegt die Datei als ".sxc" vor, was von allen Office-Versionen gelesen werden kann.
-
https://github.com/cscode2000/EAR_OO
