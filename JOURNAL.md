---
title: "encoder-midi-controller"
author: "Lucas Crowder"
description: "a midi controller with 4 encoders on it for sound and lighting tech"
created_at: "2026-24-09"
---

# September 24  Beginnings/ layout 
![layout](assets/Screenshot(1).png)
I spent today setting up the project and designing some options for the layout of the components.



# September 26 Research 
I started today out with doing some research on the parts and components I would need.  
  
I needed a controller and at first i was looking at the teency 4.0/4.1 but with its much higher cost and the fact that it is overkill for this situation I ended up going with the raspberry pi pico. 

for the encoders I am going with a bourns 64ppr optical encoder [EM14R0A-M25-L064S](https://www.mouser.com/en/ProductDetail/Bourns/EM14R0A-M25-L064S?qs=1lgFYnuX1%252BwmsRG7w4OCUg%3D%3D) it is on the pricey side but this is a project for my brother and he wanted high quality encoders and he is paying for a lot of it. 
![encoder choice](assets/Screenshot(2).png)

there is an issue that the encoder runs at 5v and the pico can only handle signals at 3.3v so I found an IC [74LVC245 - Breadboard Friendly 8-bit Logic Level Shifter](https://www.adafruit.com/product/735#description) that coverts the voltage and it doesn't degrade signal edges like Resistor Voltage Dividers and MOSFET-based Modules.

# September 30  making the schematic
Today I got done with the schematic portion of the PCB
![schematic of PCB](assets/Screenshot(3).png)

i am not the most experienced with ECAD so it took a while to get done  


