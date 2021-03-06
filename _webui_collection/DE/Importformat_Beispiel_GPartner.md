---
title: Formatbeispiel für den Import von Geschäftspartnerdaten
layout: default
tags:
  - Datenverwaltung
  - Datenimport
  - Geschäftspartnerdatenimport
lang: de
sequence: 10
ref: import_format_example_bpartner
---

## Überblick
Für den Geschäftspartnerdatenimport benötigst Du ein Importformat, in dem die **DB-Tabelle** *Import - Geschäftspartner* eingestellt ist.

In dem folgenden Beispiel wird der Dateninhalt aus einer Datei einer Tabellenkalkulationssoftware (hier z.B. eine *Excel*-Datei vor der [Konvertierung in eine CSV- oder TXT-Datei](Importdatei_nuetzliche_Hinweise)) dem Importformat für Geschäftspartnerdaten gegenübergestellt:

![](assets/GPartnerimport_Excel-Tabelle_Format.png)

### Erläuterungen zum Beispiel
- Die **Spalte A** der Excel-Tabelle (*Suchschlüssel*) steht an erster Stelle, d.h. das entsprechende Formatfeld bekommt die **Start-Nr. 1**. Demzufolge erhält das Formatfeld für die **Spalte B** die **Start-Nr. 2** usw.<br> Die **Reihenfolge** der Formatfelder ist dabei unerheblich.
 >**Hinweis:** metasfresh erwartet ***keine Spaltennamen*** in der Importdatei. Alleine die ***Position*** der Spalte muss mit der Startnummer übereinstimmmen.

- Der **Name** des Formatfeldes ist frei wählbar und muss nicht mit der Benennung der Spalte aus der Importdatei übereinstimmen.
- Die **Spalte** des Formatfeldes bestimmt, wohin metasfresh den Inhalt der Spalte aus der Importdatei übertragen soll.
- Der **Datentyp** bestimmt, ob es sich bei den Importdaten z.B. um eine *Zeichenfolge* oder *Zahl* handelt.

### Einige nützliche Hinweise

| Information | Beispiel | Hinweis |
| :---: | :--- | :--- |
| Region | • NRW<br> • AZ | NRW = **N**ord**r**hein-**W**estfalen<br> AZ = **A**ri**z**ona<br> (*Das Akronym bzw. den **Namen** einer Region kannst Du unter dem Menüpunkt "[Land, Region](Menu)" unter der Registerkarte "Region" des jeweiligen Ländereintrags nachschauen.*) |
| ISO-Ländercode | DE | DE = **De**utschland<br> Zweistelliger Buchstabencode (gem. ISO 3166-1 Alpha-2).<br> (*Den ISO-Ländercode kannst Du unter dem Menüpunkt "[Land, Region](Menu)" nachschauen.*) |
| Gruppen-Schlüssel	| • Standard<br> • 1000001 | **Suchschlüssel** der Geschäftspartnergruppe. _**Achtung:** Nicht der Name!_<br> Lege die Geschäftspartnergruppe erst in metasfresh an und verwende dann hier ihren Suchschlüssel.<br> (*Den Suchschlüssel kannst Du unter dem Menüpunkt "[Geschäftspartnergruppen](Menu)" im jeweiligen Eintrag nachschauen.*) |
| OrgValue | metasfresh AG | **Suchschlüssel** der Organisation. _**Achtung:** Nicht der Name!_<br> (*Den Suchschlüssel kannst Du unter dem Menüpunkt "[Organisation](Menu)" nachschauen.*) |
| Standortdaten | • Straße und Nr.<br> • PLZ<br> • Ort<br> • Region<br> • ISO Ländercode | Damit [Standortdaten](Adresse_erfassen_Tab) importiert werden können, müssen mindestens **Ort** und **ISO Ländercode** angegeben sein.<br><br> Standortdaten wie **Straße und Nr.**, **PLZ** oder **Region** werden nur importiert, wenn sowohl **Ort** als auch **ISO Ländercode** vorhanden sind. |
| Global Location Number (GLN) | 1234567890128 | Zum Import einer **GLN** müssen sowohl **Ort** als auch **ISO Ländercode** vorhanden sein. |
| Webadresse (URL) | [**https://**metasfresh.com/](https://metasfresh.com/ "metasfresh Homepage") | Damit eine **URL** nach dem Import gültig wird, muss diese mit dem Internetprotokollakronym beginnen (z.B. `https://`). |

## Nächste Schritte
- [Geschäftspartnerdaten importieren](GPartnerdaten_importieren).
