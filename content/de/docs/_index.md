---
title: "Documentation"
linkTitle: "Documentation"
weight: 20
menu:
  main:
    weight: 20
---

Hector 9000 ist ein Cocktailautomat, der 12 verschiedene Getränke
dosieren kann. Entstanden ist Hector 9000 Anfang 2018 als Nachfolger
von Onkel Hector, einem reinen Gin-Tonic-Automaten. Bei der
Entwicklung wurde versucht, möglichst viele Teile durch 3D-Druck, ohne
Support, herzustellen.\

Im Gegensatz zu vielen anderen Barbots werden keine Peristaltikpumpen
verwendet, wodurch eine Förderung von kohlensäurehaltigen Getränken
möglich ist. Die Flüssigkeiten werden durch einen leichten Überdruck
in den Flaschen gefördert, gleichzeitig wird die geförderte Menge
durch eine Waage ermittelt. Ist genug von einem Getränk dosiert
worden, werden die zum Getränk gehörigen Silikonschläuche
abgequetscht. Die Getränke kommen dabei nicht mit beweglichen Teilen
in Berührung. Ist ein Cocktail fertiggestellt, betätigt Hector seine
Glocke.\

Das Herz von Hector 9000 ist ein Raspberry Pi 3B. Der Pi übernimmt die
Ablaufsteuerung und stellt auf einem 7"-Touch-Display das UI dar. Die
Software ist in Python 3 geschrieben, zur grafischen Darstellung wird
Javascript und HTML genutzt.