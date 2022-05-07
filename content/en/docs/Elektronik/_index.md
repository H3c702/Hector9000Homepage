---
title: "Elektronik"
linkTitle: "Elektronik"
weight: 2
---
### General

We decided to realize the power supply of Hector 9000 with a PC power
supply. It is recommended to place the voltage outputs of the power
supply unit on terminal blocks and to carry out the cable routing in
wiring channels. We have fused the supply voltage of the LED strips,
also on terminal blocks. It is also useful to make the connections
between the modules by crimped connectors.

![Power supply](/images/psu.JPG){#psu height="8cm"}

![Backpanel removed](/images/electronic_overview.JPG){#electronic_overview
height="8cm"}

### Wiring

The interconnection of the individual components
(Fig. [15](#GPIO_overview){reference-type="ref"
reference="GPIO_overview"}) is relatively simple. We recommend placing
the HX711 board as close as possible to the Raspberry Pi in order to
keep the I2C lines short. For the illumination two WS2812B LED strips
were connected in parallel to the GPIO of the RPi. There are 15 LEDs in
the lower compartment (bottles) per line and 30 LEDs in the upper
compartment of the housing. The pinout of the Raspberry Pi can be seen
in Fig. [16](#GPIO_connections){reference-type="ref"
reference="GPIO_connections"}. The optional all-round light must be
switched via a transistor (Fig. [17](#rundumlicht){reference-type="ref"
reference="rundumlicht"}).

![Wiring overview](/images/RPi_GPIO_overview.svg){#GPIO_overview
height="6cm"}

![GPIO connections](/images/Hector9000_connections.svg){#GPIO_connections
height="9cm"}

![Connecting the all-round light](/images/rundumlicht.svg){#rundumlicht
height="5cm"}
