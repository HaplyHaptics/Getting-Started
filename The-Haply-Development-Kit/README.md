# The Haply Development Kit


<img src="media/Haplybox.JPG" width="600">

## Introduction

The Haply Development Kit is a robust and adaptable open-source hardware
development platform for haptic applications. Designed to be accessible
to novices and experts alike, the kit allows you to quickly setup and
interact with a haptic simulation using a 2-degree-of-freedom pantograph
device. Instructions below will take you through assembly of the device.

Visit [www.haply.co](http://www.haply.co) for more information

## Kit Overview

The Haply development kit contains all the mechanical and electrical
components needed to construct your own 2-degree-of-freedom pantograph
device.

The Haply M3 board is capable of controlling up to up to 4 motors, and the
M0 board is capable of controlling 2. Experienced users will be able to develop
their own unique designs ranging from 1-degree-of-freedom to
4-degree-of-freedom haptic devices.

## Kit Contents

• 1x Acrylic Plate**    
• 2x Acrylic L2 Arm Linkages  
• 1x Board Case Bottom  
• 1x Board Case Top  
• 2x Development Board Extension Wires  
• 1x End Effector and Arm Assembly Screws   
• 1x Haply Board  
• 1x Large and Small Allen Keys  
• 2x Motors  
• 1x Power Supply  
• 1x Micro USB Cable  
• 4x Suction Cup Feet  
• 1x Wire Adapter Board  
• 1x 3D Printed Base**  
• 1x 3D Printed End Effector  
• 2x 3D Printed L1 Arm Linkages  
• 1x 3D Printed Motor Housing  
• 1x 3D Printed Motor Stand  
• 1x Screw Set  

** Depending on when you ordered your kit, these two components will already be attached

Haply Board
=================================

<img src="media/image000a.JPG" width="400"> <img src="media/image000b.JPG" width="400">

## Overview

The Haply board is a highly robust and configurable open-source
platform ideal for haptic and robotic development.

Based on the Arduino framework, both Haply boards use the  32-bit AT91SAM3X8E
ARM microcontroller as their core. Side rail pin connections are
maintained giving the Haply board compatibility to a majority of
available Arduino Shields.

L298P Motor drivers are incorporated into the board, allowing the
Haply board the ability to precisely control up to four DC
motors (2 motors for the M0 board).

The Haply board is fully compatible with the Arduino IDE and
programmable through the Native USB port.

## Technical Specifications

**Warning: MCU I/O pins have maximum tolerated voltage of 3.3V**

### M0

-   Measures 80mm X 32mm x 8mm

-   ATSAMD21G18 32-bit ARM MCU @48MHz

-   Native USB port for programming and debugging

-   Contains 2 motor control ports

-   3.3V operating voltage

-   5 - 12V recommended input voltage

-   2A Max output current per motor port

-   Reset and Erase Button

### M3

-   Measures 100mm X 59.5mm x 8mm

-   AT91SAM3X8E 32-bit ARM MCU @84MHz

-   Native USB port for programming and debugging

-   Contains 4 motor control ports

-   3.3V operating voltage

-   5 - 12V recommended input voltage

-   2A Max output current per motor port

-   Reset and Erase Button

# Haply Dev Kit Assembly Instructions


## Haply Development Kit Contents  

<img src="media/image001.JPG" width="900">

1.   1x Power supply                 
2.   1x Micro USB cable               
3.   4x Suction cup feet             
4.   1x 3D printed motor housing     
5.   2x Motors                       
6.   1x 3D printed motor stand       
7.   1x Board Case Top              
8.   2x 3D printed L1 arm linkages   
9.   2x Acrylic L2 arm linkages      
10. Large and small Allen Keys
11. End effector and arm assembly screws
12. 2x Dev board extension wires
13. 1x Wire adapter board
14. 1x Acrylic plate
15. 1x Board Case Bottom
16. 1x 3D printed Base
17. 1x Haply Board
18. 1x 3D printed end effector
19. 1x Screw Set  
        • 2x 2-56 screws (Motor stand)  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  •  4x M2 screws (Motors)  
        • 3x 2-56 screws (Acrylic Plate)**   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   • 2x 2-56 screws black (Wire adapter board)  
        • 4x 2-56 screws (Board Case)***       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  • 1x ¾" 4-40 screw (Motor stand)  
        • 2x 4-40 set screws black (Arm linkages)  

** If the acrylic plate and 3D printed base are already attached, this set of screws aren't needed and wont be included  
*** If you ordered an M0 board, the case only requires one 2-56 screw. Only one will be included.

Device Assembly
===============

Before proceeding with the device assembly, please check over the
inventory of the kit contents from the previous section. You will need also
need a small flat head screw driver and a small Philips head (cross
head) screw driver for device assembly.

Please peel off all protective plastics on the acrylic pieces, and
attach the acrylic plate to the 1x 3D printed Base with 3x
2-56 screws using the appropriate Allen key.

***Warning: Take care not to over tighten screws**

<img src="media/image001b.JPG" width="600">

  ------------------------------------------------------------------------------------ -----------------------------------------------------------------------------------     


## Part A: Motor Housing Assembly

<img src="media/image002.jpg" width="400">

**Section parts list:**

-   1x 3D printed motor housing
-   2x Motors
-   4x M2 screws    

1.  Insert the motors into the motor housing with the cable slipped through the gap in the housing. Make sure the motors are
    pushed all the way to the bottom.

2.  Align the holes from the motor housing with the screw holes on the
    motors and use two M2 screws to fix each motor to the motor housing using a Philips head screwdriver.

    <img src="media/image004.jpg" width="400"> <img src="media/image003.jpg" width="400">  

## Part B: L1 Arm Linkage Assembly

<img src="media/image005.jpg" width="400">

**Section parts List:**

-   1x Completed assembly from previous section   
-   2x 4-40 set screws
-   2x 3D printed L1 arm linkages

1.  Insert the 4-40 set screws part way into both of the L1 arm
    linkages.

2.  Before attaching the L1 arm linkages to the motors, make sure the
    flat side of the motor shaft can be aligned with the set screw.

3.  Once the motor shafts and the set screws are aligned, attach the arm
    linkages. Ensure that arm linkages are oriented such that the cut-outs are on the inner side of the assembly with the flat side facing up.

4.  Move the arms around to ensure connection to motor shaft.

<img src="media/image006.jpg" width="400"> <img src="media/image007.jpg" width="400">

## Part C: Motor Stand Assembly

 <img src="media/image008.jpg" width="400">

 **Section parts List:**   

 -   1x Completed assembly from previous section
 -   1x 3D printed motor stand
 -   1x Wire adapter board
 -   2x M2 screws black
 -   1x ¾" 4-40 screw

1.  Attach the motor cables into the wire adaptor board as shown.

2.  Slide the motor stand onto the assembly with the wire adaptor above

3. Insert and tighten the M2 screws into the motor housing.


<img src="media/image009.jpg" width="400">   <img src="media/image010.jpg" width="400">

1.  Attach the ¾" 4-40 screw in the front using the flathead screwdriver. The 4-40 screw will go through the motor stand into the small hole on the motor housing.


<img src="media/image011.jpg" width="400">

------------------------------------------------------------------------------------- -------------------------------------------------------------------------------------

## Part D: L2 Arm Linkage Assembly

<img src="media/image012.jpg" width="400">

**Section parts List:**

-   1x Completed assembly from previous section
-   2x L2 arm linkages
-   2x Plastic joints assembly
-   1x End-effector handle assembly

1.  Place a plastic joint cap into the L1 arm linkage.

2.  Before connecting a L2 arm linkage, make sure a Teflon washer is
    sandwiched between the two linkages.

<img src="media/image013.jpg" width="400">   <img src="media/image014.jpg" width="400">

1.  Install the second L2 arm linkage with a Teflon washer sandwiched
    between the L1 and L2 arm linkages as pictured.

2.  Make sure the second L2 arm is installed on the opposite side
    compared to the first.

3. On the opposite side of the assembly, place the L1 arm under the L2 arm so that the end of one L2 arm linkage is below the other. This will allow for mounting of the end effector.


<img src="media/image015.jpg" width="400">   <img src="media/image016.jpg" width="400">

1.  Place the end-effector cap into the top L2 arm linkage, sandwich the
end-effector handle washer between the two L2 arm linkages and
finally screw in the end-effector screw to complete this section.

  <img src="media/image017.jpg" width="400">

  ------------------------------------------------------------------------------------- -------------------------------------------------------------------------------------


## Part E: Base Attachment Assembly

<img src="media/image018.jpg" width="400">

**Section parts List:**  

-   1x Completed assembly from previous section
-   2x 2-56 screws
-   1x Acrylic top plate/ 3D printed base assembly


  <img src="media/image019.jpg" width="400">   

1.  Place the completed assembly into the top plate.

2.  Screw the assembly into the top plate on both sides.

 <img src="media/image020.jpg" width="400">

 ------------------------------------------------------------------------------------

## Part F: Haply Board Installation

<img src="media/image021.jpg" width="400">

**Section parts List:**

-   1x Completed assembly from previous section
-   1x Haply board  
-   2x Dev board extension wires
-   1x Board Case Top
-   1x Board Case Bottom
-   4x 2-56 screws

1.  Connect the dev board extension wires to the Haply board as shown in the picture.

2. Lay the Haply board upside down the case such that the wires extend from the open side of the case. All motor ports should be accessible.

<img src="media/image022.jpg" width="400">   <img src="media/image023.jpg" width="400">

1. Place and tighten the case top using the 2-56 screws

2. Attach the dev board extension wires as pictured. This will ensure correct function of the Haply software.

<img src="media/image024.jpg" width="400"> <img src="media/image025.jpg" width="400">

*** If you ordered an M0 board, assemble as seen below. You'll only need one 2-56 screw.

<img src="media/image023a.JPG" height="300">  <img src="media/image025a.JPG" height="300">

------------------------------------------------------------------------------------ ------------------------------------------------------------------------------------

## Part G: Base Plate Assembly

<img src="media/image026.jpg" width ="400">

**Section parts List:**  

 -   1x Completed assembly from previous section
 -   1x Acrylic bottom plate
 -   4x Suction cup feet


1.  Place the bottom plate and screw in each of the suction cup feet.

2.  Upon completion the device will be ready for use!

<img src="media/image027.jpg" width="400">   <img src="media/image028.jpg" width="400">
------------------------------------------------------------------------------------- -----------------------------------------------------------------------------------

## Part H: Connectivity Wiring

- 1x Power supply                 
- 1x Micro USB cable    

Although not a part of assembly, the power supply and micro USB cable are attached as shown below

<img src="media/image029.jpg" width="400">  <img src="media/image030.jpg" width="400">

------------------------------------------------------------------------------------ ------------------------------------------------------------------------------------


**The completed Haply Development Kit**


    The Haply project is intended to provide novice designers and developers
	a platform from which to explore the field of haptics. The Haptics Application
	Programming Interface (hAPI) is a modular tool that lets users quickly assemble
	a variety of haptic robots, ranging from one to four degrees of freedom, using
	the same set of hardware and programming tools. We hope people will be inspired
	to build new tools to interface with the hAPI and share them with the community.

	If you have any questions or concerns please contact us at haplyrobotics@gmail.com

	Enjoy!


    Copyright (C) <2017>  <The Haply Project: Colin Gallacher & Steven Ding>

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
