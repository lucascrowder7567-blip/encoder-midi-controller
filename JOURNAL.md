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

I was luckily able to find a symbol for the encoders on the vendors website. I wasn't as lucky with the logic level shifter IC and as I am not the most experienced with that part of ECAD it took a while but I got it done.
![picture of IC symbol](assets/Screenshot(10).png)

# October 3 PCB layout
Today I started on the layout and routing for the PCB
![layout at end of October 3rd](assets/Screenshot(8).png)

I was struggling to find a location to place the pico where I would be out of the way and I would still be able to access all the needed pins easily so I ended up figuring out that I could surface mount the board so that I could use the back copper under the pads to rout traces.
![picture of SMD pico](assets/Screenshot(7).png)



# October 5 cleaning up and finishing PCB
Today I finished up the PCB routing
![layout at end of October 5th](assets/Screenshot(9).png)

there was not much I did but clean things up. I had to move a number of the traces on the back copper to the front copper so the ground plane was less broken up

# October 13 3D MODELS
Today I made progress on the 3d models for the PCB and case
![3D models at end of October 13th](assets/Screenshot(6).png)


# October 14 continuing on case model


