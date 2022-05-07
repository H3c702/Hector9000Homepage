---
title: "Mechanik"
linkTitle: "Mechanik"
weight: 1
---

### Waage

Um die dosierten Mengen zu ermitteln, wird eine Wägezelle in Verbindung
mit einem HX711 verwendet. Vor der Montage der gedruckten
Kunststoffteile muss der Überlauf in die Waagschale eingeklebt werden.
Die Befestigung der Waage erfolgt von oben durch die Tischplatte. Der
Abstandshalter und der Überlauf müssen abhängig von der Dicke der
Tischplatte angepasst werden, zwischen Tischplatte und Waagschale sollte
ein Spalt von 1 mm sichbar sein. Als Anschlusskabel wurde ein
CAT5e-Kabel verwendet. Auf der Unterseite des Gehäuses besteht die
Möglichkeit, einen Schlauch mit 10 mm Innendurchmesser für den Überlauf
anzuschließen. Für die Montage der Waage hat sich folgende Reihenfolge
bewährt:

1.  Kabelverschraubung im Gehäuse befestigen,

2.  Gehäuse und Wägezelle unter der Tischplatte positionieren,

3.  Wägezelle von oben anschrauben,

4.  Abstandshalter und Waagschale befestigen,

5.  Kabel verlöten,

6.  Deckel verschrauben.

![Waage mit Glas](/images/scale_glass.JPG){#scale_glass height="8cm"}

![Waage von unten](/images/scale_bottom.JPG){height="8cm"}

### Pumpe

Um den Überdruck in den Flaschen zu erzeugen, verwenden wir eine
Luftpumpe für Aquarien. Da die komplette Elektronik mit max. 12 VDC
laufen soll, haben wir uns für eine 12V-Pumpe von Schego entschieden.
Die Auswahl der Pumpe ist relativ unkritisch, da der benötigte Überdruck
und die Fördermenge gering sind. Es sollte lediglich darauf geachtet
werden, dass die Pumpe ölfrei arbeitet. Da die Pumpe nur über ein
einziges Loch zur Befestigung verfügt, wurde eine Halterung konstruiert.
Folgende Reihenfolge bei der Montage hat sich bewährt:

1.  Jeweils an einem Ende der Gewindestangen 2 Muttern aufschrauben und
    kontern. Eine Mutter sollte bündig mit der Gewindestange
    abschließen, die Schlüsselflächen der Muttern müssen in einer Flucht
    stehen.

2.  Gewindestangen in die dafür vorgesehenen Löcher stecken,

3.  Halterung im Gehäuse festschrauben,

4.  Pumpe einsetzen und mit den U-Profilen festklemmen (optional mit
    Moosgummistreifen unter den U-Profilen),

5.  Muttern an den U-Profilen kontern oder mit Loctite verkleben.

![Luftpumpe](/images/pump.JPG){#pump height="8cm"}

### Ventile

Um die Dosierung der Flüssigkeiten zu realisieren, wurden für unseren
Cocktailautomaten Quetschventile konstruiert, welche immer beide
Schläuche (Luft *und* Flüssigkeit) einer Zutat gleichzeitig öffnen bzw.
schließen.\
Die benötigten Kunststoffteile für die Ventile können ohne Support
gedruckt werden. Die (optionale) Abdeckung wurde für unseren Automaten
mit einem CO~2~-Laser aus transparentem PMMA geschnitten. Es ist darauf
zu achten, dass die Servos originale *TowerPro MG996R* sind. Es gibt
Servos mit gleicher Bezeichnung von No-Name-Anbietern, aber diese Servos
können sich in den Außenabmessungen teilweise erheblich von den
originalen Servos unterscheiden. Die bei den Servos mitgelieferten
runden Servoarme müssen auf den Innendurchmesser der Nocken angepasst
werden. Hierbei ist besondere Sorgfalt notwendig: Sitzen die Servoarme
exzentrisch im Nocken, wird das Ventil nicht richtig absperren. Unsere
Servoarme wurden auf einer CNC-Fräse mit einem sehr scharfen Holzfräser
bearbeitet. Die Befestigungslöcher für die Servoarme werden am besten
gebohrt, indem der Nocken als Schablone genutzt wird. Die Schrauben zur
Verbindung von Nocken und Servoarm werden mit Loctite gesichert. Bei den
Zungen ist darauf zu achten, dass sie aus einem Material mit guten
Gleiteigenschaften gefertigt werden. Unsere Zungen wurden aus *Iglidur
I150* gedruckt. Die Zungen in den Ventilen von Onkel Hector haben schon
einige hundert Zyklen hinter sich und funktionieren immer noch
einwandfrei. Alternativ könnten die Zungen aus PET gedruckt werden, dies
wurde allerdings noch nicht getestet. Damit die Ventile bündig mit der
Rückwand sitzen, müssen Auschnitte für die Servos hergestellt werden
(Abb. [4](#valve_rear){reference-type="ref" reference="valve_rear"}).
Zur Befestigung der Ventile haben sich Einschlagmuttern bewährt.

![Ventile](/images/valve_front.JPG){#valve_front height="8cm"}

![Ventile von hinten](/images/valve_rear.JPG){#valve_rear height="8cm"}

### Arm

Um den Füllvorgang komfortabler zu gestalten, ist der Arm mit dem
Dosierkopf im Normalzustand eingefahren (Abb.
[\[arm_front_in\]](#arm_front_in){reference-type="ref"
reference="arm_front_in"}). Wird der Dosiervorgang gestartet, fährt der
Arm nach vorne. Alle benötigten Kunststoffteile lassen sich ohne Support
drucken. Der Gleiteinsatz sollte aus einem Material mit guten
Gleiteigenschaften gefertigt werden. Unser Gleiteinsatz wurde aus
*Iglidur I150* gedruckt. Alternativ könnte der Gleiteinsatz aus PET
gedruckt werden, dies wurde allerdings noch nicht getestet. Der Ausleger
besteht aus einem Aluminiumprofil mit 15.5 mm Kantenlänge. Solche
Profile sind in fast jedem deutschen Baumarkt zu finden. Das Ritzel wird
auf die Welle des Motors gepresst und braucht keine weitere Sicherung.
Um die Zahnstange an dem Ausleger zu befestigen, wurden
M3-Blindnietmuttern in das Profil eingesetzt. Der Dosierkopf wird mit
einer selbstschneidenden Schraube im Profil gesichert. Der Auslöser wird
mit dem Ausleger verklebt. Der Auslöser weist ein Loch auf. Durch dieses
Loch wurde ein Kabel geführt, um ein optionales Rundumlicht auf dem Arm
mit Strom zu versorgen.\
Bei der Montage des Arms ist darauf zu achten, dass die untere Schraube
von hinten durch die Bohrung geführt und mit einer regulären Mutter
festgeschraubt wird. Die oberen Schrauben werden von vorne durch die
Rückwand gesteckt und verschraubt. Auf der unteren Schraube kann nun mit
einer Rändelmutter der Tropfenfänger montiert werden (Abb.
[\[drip\]](#drip){reference-type="ref" reference="drip"}).

![Arm Rückseite](/images/arm_rear.jpg){#arm_rear height="8cm"}

![image](/images/nodrip.JPG){height="8cm"}
![image](/images/yodrip.JPG){height="8cm"}

### Glocke

Bei dem Nachbau der Mechanik für die Glocke ist darauf zu achten, dass
der Mittelpunkt der Glocke 100 mm von der Drehachse des Arms entfernt
ist. Zur Befestigung der Glocke ist eine Halterung vorgesehen (Abb.
[6](#bell_mount){reference-type="ref" reference="bell_mount"}). Um die
notwendigen Löcher in die Glocke zu bohren, wird die Halterung als
Bohrlehre benutzt. Die Montage des Fingers an der Rückwand ist
eigentlich selbsterklärend. Zur Befestigung der Motorhalterung
(Bell_servo-bracket.stl) an der Rückwand ist es ratsam, Einschlagmuttern
oder Gewindeeinsätze zu verwenden, so kann der Finger später leicht
justiert werden (Abb. [8](#finger){reference-type="ref"
reference="finger"}).

![Befestigung der Glocke](/images/bell_mount.JPG){#bell_mount height="8cm"}

![Glocke](/images/bell.jpg){#bell height="8cm"}

![Finger mit Halterung](/images/finger.JPG){#finger height="8cm"}

### Schläuche

Um Flüssigkeiten und Luft zu transportieren, werden Silikonschläuche mit
6 mm Außendurchmesser und 4 mm Innendurchmesser verwendet. Es muss auf
jeden Fall darauf geachtet werden, dass die Schläuche für den Einsatz
mit Lebensmitteln vorgesehen sind. Um die Schläuche durch das Gehäuse,
die Ventile und den Dosierkopf zu führen, hat es sich bewährt, ein Ende
schräg abzuschneiden. Pro Zutat werden zwei Schläuche durch ein Ventil
geführt. Ein Schlauch leitet die Flüssigkeiten von der Flasche zum
Dosierkopf, der andere Schlauch verbindet Luftpumpe und Flasche. Bei der
Verlegung der Schläuche im Gehäuse muss darauf geachtet werden, dass
sich die Schläuche nicht mit dem Arm verheddern. Wir haben dafür einfach
Kabelbinder benutzt (Abb. [9](#hoses){reference-type="ref"
reference="hoses"}).

![Führung der Schläuche](/images/hoses.JPG){#hoses height="8cm"}

### Stopfen

Die Stopfen bestehen aus einem 3D-gedruckten Kern und einer konischen
Dichtung. Die Dichtung ermöglicht es, mit einer Art von Stopfen
verschiedene Getränkeflaschen anzuschließen. Die Dichtungen können aus
dem Gastronomiebedarf bezogen werden. Beim Druck der Kerne sollte
lebensmittelechtes Filament verwendet werden. Auf einer Seite des
Stopfen werden die Schläuche angeschlossen, die zu den Ventilen führen
(Wichtig: Luft- und Getränkeschläuche nicht verwechseln!). Auf der
anderen Seite des Stopfens wird ein Stück Silikonschlauch angeschlossen,
das bis zum Boden der Flasche reicht.

![Stopfen](/images/plugs.JPG){#plugs height="8cm"}

### Spültrichter

Da zum Spülen der Schläuche eine Menge Wasser und Zeit notwendig ist,
macht es wenig Spaß, während des Spülprogramms die ganze Zeit neben
Hector zu stehen und volle Gläser auszuleeren. Wir haben deswegen einen
Spültrichter konstruiert, der anstelle eines Glases auf die Waage
aufgesetzt wird und das Abwasser direkt in einen Eimer oder Ausguss
befördert. Der Spültrichter kann ohne Support gedruckt werden. Die
Schlauchtülle ist für einen Silikonschlauch mit 10 mm Innendurchmesser
konzipiert.

![Spültrichter](/images/funnel.JPG){#funnel height="8cm"}

### Gehäuse

Das Gehäuse besteht aus 25 mm-Aluminiumprofilen, die mit
Aluminiumblechen und PMMA-Platten beplankt wurden. Das Blech, an dem die
Waage befestigt wurde, sowie das Blech, welches die Ventile trägt,
wurden zusätzlich mit einer MDF-Platte verklebt. Vor dem Verkleben
wurden auf der Vorderseite der MDF-Platten Einschlagmuttern eingesetzt,
um später die Hutschienen und die Pumpe zu befestigen. Die PMMA-Platten
und ein Großteil der Bleche wurden mit 4 mm-Blindnieten befestigt. Die
Befestigung der Rückwand erfolgt durch M4-Schrauben. Als Gegenstück zu
den Schrauben wurden in die Profile Blindnietmuttern eingesetzt. Es wird
dringend empfohlen, zur Bearbeitung der Bleche und Profile spezielle
Blechbohrer zu verwenden, ansonsten kann es zu Problemen beim Einsetzen
der Nieten kommen. Das Gehäuse ist in der Stückliste nicht
berücksichtigt, hier soll jeder seiner Kreativität freien Lauf
lassen.[^1]

![Hector 9000](/images/hector9000.JPG){#hector9000 height="8cm"}

### Display

Zur Auswahl der Drinks haben wir uns für ein 7"-Display mit
Touch-Funktion über USB entschieden. Die USB-Variante ist notwendig, da
die GPIOs für andere Funktionen genutzt werden. Das Display ist an einer
Querstrebe des Gehäuses befestigt. Für den Transport kann das Display in
das Gehäuse gedreht werden (Abb.
[\[display_half_in\]](#display_half_in){reference-type="ref"
reference="display_half_in"}). In dem gedruckten Gehäuse für das Display
sind 3 Löcher für die Montage an dem Rahmen. Für die Befestigung werden
nur zwei Löcher benötigt: das mittlere Loch und ein äußeres. Das Display
wird mittels Blindnietmuttern und Rändelschrauben mit dem Rahmen
verschraubt. Um das Display zu drehen, wird die äußere Schraube entfernt
und die mittlere Schraube gelöst.

