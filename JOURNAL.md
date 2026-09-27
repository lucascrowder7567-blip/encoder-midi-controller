---
title: "encoder-midi-controller"
author: "Lucas Crowder"
description: "a midi controller with 4 encoders on it for sound and lighting tech"
created_at: "2026-24-09"
---

# September 24  Beginnings/ layout 
![layout](assets/Screenshot(9).png)
I spent today setting up the project and designing some options for the layout of the components.



# September 26 Research 
I started today out with doing some research on the parts and components I would need.  
  
I needed a controller and at first i was looking at the teency 4.0/4.1 but with its much higher cost and the fact that it is overkill for this situation I ended up going with the raspberry pi pico. 

for the encoders I am going with a bourns 64ppr optical encoder (EM14R0A-M25-L064S) it is on the pricey side but this is a project for my brother and he wanted high quality encoders and he is paying for a lot of it. 

there is an issue that the encoder runs at 5v and the pico can only handle signals at 3.3v so I found an IC that coverts the voltage and it doesn't degrade signal edges like Resistor Voltage Dividers and MOSFET-based Modules.


