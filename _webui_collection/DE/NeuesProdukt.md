---
title: Wie lege ich ein neues Produkt an?
layout: default
tags:
  - Stammdaten
  - Produkt
lang: de
sequence: 10
ref: newproduct
---

## Schritte
1. [Gehe ins Menü](Menu) und öffne das Fenster "Produkt".
1. [Lege ein neues Produkt an](Neuer_Datensatz_Fenster_Webui).
1. Fülle das Feld **Artikelname** aus.
 >**Hinweis:** Dieser Name erscheint auf den Belegen wie Auftragsbestätigung usw.

1. Wähle eine **Artikelkategorie** aus.
 >**Hinweis:** Die Artikelkategorie kann verwendet werden, um die Rabattierung, Kontierung und den Merkmalsatz eines Artikels zu steuern.

1. Wähle eine **Maßeinheit** für den Artikel aus.
 >**Hinweis:** Dies ist die Maßeinheit für die Bestandsführung und ist ***nicht zu verwechseln*** mit der Verkaufsmengeneinheit, die bei der Preisvergabe festgelegt wird!

1. Fülle das Feld **Artikelnummer** aus.
 >**Hinweis 1:** Diese Nummer erscheint auf den Belegen wie Auftragsbestätigung usw.<br><br>
 >**Hinweis 2:** Diese Nummer kann auch automatisch vergeben werden.

## Nächste Schritte
- [Einkaufs- oder Verkaufspreis hinterlegen](ProduktPreis).
- Produkt für die Produktion konfigurieren.

## Beispiel
![](assets/neuesprodukt.gif)

## Weitere wichtige Felder
- Das Feld **Maßeinheit** bestimmt, in welcher Einheit der Artikel im Bestand geführt wird (Bestandsmengeneinheit).
 >**Hinweis 1:** Sobald der erste Beleg existiert, in dem dieser Artikel verwendet wird, kann die Bestandsmengeneinheit nicht mehr ohne weiteres geändert werden.<br><br>
 >**Hinweis 2:** Eine abweichende Verkaufsmengeneinheit kann unter der Registerkarte "Preis" losgelöst von der Bestandsmengeneinheit definiert werden. In diesem Fall muss eine [Maßeinheitenumrechnung](Masseinheiten_umrechnen) angelegt werden.

- Das Feld **Artikelart** bestimmt, um welche Art von Artikel es sich handelt.

|	Option | Effekt |
|:	------------ | ------------- |
|	Artikel | Materieller Artikel, z.B. Stückgut, Verpackung usw. (Standard)|
|	Dienstleistung | Immaterieller Artikel, z.B. Serviceleistung|
|	Erfolgskonto | Steuert Kontierung|
|	Ressource | Artikel, der zeitlich nur einmal belegt werden kann, z.B. eine Maschine|

- Das Feld **Lagerhaltig** bestimmt, ob der Artikel (insofern die Artikelart auf der Option "Artikel" steht) im Bestand geführt wird.
- Das Feld **Eingekauft** bestimmt, ob der Artikel im Einkauf zur Verfügung steht.
- Das Feld **Verkauft** bestimmt, ob der Artikel im Verkauf zur Verfügung steht.
