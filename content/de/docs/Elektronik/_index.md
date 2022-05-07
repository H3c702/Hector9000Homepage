---
title: "Elektronik"
linkTitle: "Elektronik"
weight: 2
---

### Allgemeine Hinweise

Wir haben uns entschieden, die Spannungsversorgung von Hector 9000 durch
ein PC-Netzteil zu realisieren. Es ist empfehlenswert, die
Spannungsausgänge des Netzteils auf Reihenklemmen zu legen und die
Kabelführung in Verdrahtungskanälen vorzunehmen. Die Versorgungsspannung
der LED-Streifen haben wir, ebenfalls auf Reihenklemmen, abgesichert.
Außerdem lohnt es sich, die Verbindungen zwischen den Modulen durch
aufgecrimpte Stecker herzustellen.

![Spannungsversorgung](/images/psu.JPG){#psu height="8cm"}

![Geöffnete
Rückseite](/images/electronic_overview.JPG){#electronic_overview
height="8cm"}

### Schaltung

Die Verschaltung der einzelnen Komponenten (Abb.
[15](#GPIO_overview){reference-type="ref" reference="GPIO_overview"})
ist relativ simpel. Wir empfehlen, das HX711-Board möglichst nah am
Raspberry Pi zu platzieren, um die I^2^C Leitungen kurz halten zu
könnnen. Für die Beleuchtung wurden zwei LED-Streifen (WS2812B) parallel
an einen GPIO des RPi gehängt. Pro Strang sind 15 LEDs im unteren
Bereich (Getränke) und 30 LEDs im oberen Bereich des Gehäuses
angeordnet. Die Pinbelegung des Raspberry Pi kann Abb.
[16](#GPIO_connections){reference-type="ref"
reference="GPIO_connections"} entnommen werden. Das optionale
Rundumlicht muss über einen Transistor geschaltet werden (Abb.
[17](#rundumlicht){reference-type="ref" reference="rundumlicht"}).

![Übersicht der Schaltung](/images/RPi_GPIO_overview.svg){#GPIO_overview
height="6cm"}

![GPIO-Verbindungen](/images/Hector9000_connections.svg){#GPIO_connections
height="9cm"}

![Anschluss des Rundumlichts](/images/rundumlicht.svg){#rundumlicht
height="5cm"}