---
title: "Installation"
linkTitle: "Installation"
weight: 5
---

The video shows how the Hector9000 image is written to an SD card and how the initial setup must be carried out.

{{<youtube XXcrCCRQQJg>}}

The most important points:
  - When setting up the user, the name should be "pi". 
    Since the RPI image no longer comes with a default user, this must be selected during the first boot process.
  - Ensure that I2C is set up. -> Call up RPI Config in the console and set it up there.
  - The two scripts can then be executed. 
    - Hector9000 (/home/pi/Hector9000/start.sh)
    - Hector9000WebUI (/home/pi/Hector9000WebUI/start.sh)

The Hector should then run and be ready for operation if everything is connected correctly.

Have fun :-)