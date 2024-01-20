---
title: "Installation"
linkTitle: "Installation"
weight: 5
---

In dem Video wird gezeigt wie das Image vom Hector9000 auf eine SD-Karte geschrieben wird und wie die erste Einrichtung vorgenommen werden muss.

{{<youtube XXcrCCRQQJg>}}

Die wichtigsten Punke:
  - Bei der einrichtung des Benutzers sollte der name "pi" sein. 
    Da das RPI-Image nicht mehr mit einem Defaultuser kommt muss dieser beim ersten Bootvorgang selber ausgewählt werden.
  - Sicherstellen dass I2C eingerichtet ist. -> RPI Config in der Konsole aufrufen und dort einrichten.
  - Danach können die beiden Skripte ausgeführt werden. 
    - Hector9000 (/home/pi/Hector9000/start.sh)
    - Hector9000WebUI (/home/pi/Hector9000WebUI/start.sh)

Danach sollte der Hecktor laufen und wenn alles richtig angeschlossen wurde auch betriebsbereit sein.

Viel Spaß :-)