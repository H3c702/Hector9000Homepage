---
title: "Documentation"
linkTitle: "Documentation"
weight: 20
menu:
  main:
    weight: 20
---

Hector 9000 is a cocktail machine that can pour drinks from 12
  different ingredients. Hector 9000 was created at the beginning of
  2018 as the successor to Uncle Hector, a pure Gin-Tonic machine.
  During the development we tried to make as many parts as possible by
  3D printing without support. Unlike many other barbots, peristaltic
  pumps are not used, which makes it possible to pump carbonated drinks.
  The liquids are conveyed by a slight overpressure in the bottles, at
  the same time the conveyed quantity is determined by a balance. If
  enough of a liquid has been dosed, the silicone tubes belonging to the
  liquid are squeezed off. The drinks do not come into contact with
  moving parts. When a cocktail is finished, Hector activates its bell.\
  The core of Hector 9000 is a Raspberry Pi 3B. The Pi takes over the
  process control and displays the UI on a 7" touch screen. The software
  is written in Python 3, Kivy is used to provide the graphical user
  interface.