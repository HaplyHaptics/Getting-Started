# Getting Started

Your first place to look after receiving your Haply Kit!

This repository will take you from receiving your Haply kit to building and running your first haptic demo and beyond. We'll use the following order  -

1. The Haply Development Kit - Hardware assembly
2. Software Setup - Downloading and configuring all the needed software
3. Hello Wall -  Your first haptic demo
4. FAQ - Questions we get asked a lot. If you have any we want to hear them!
5. What Next? - Exploring other repositories

__*** If you have any questions or feedback throughout your quest through this repository, reach us at info@haply.co__

If this is your first time working with Github, the best way to work with this (or any) repository is to go up to the Big Green "Clone or Download" button, and download this entire repository as a .zip file. That way you'll have all the files you need for the lesson already downloaded. You can still view this README file through your browser, or in a text editor on your computer.

The first three sections are subfolders in this repository; FAQ and What Next are written below in this README file.
## 1,2,3 Let's Get Started!
If you're looking at this in a browser, click a link to go to the subfolder. If you're reading this in a text file on your computer, navigate to the subfolder through your file manager to see the lesson. You'll find another README in each subfolder.
1. [The Haply Development Kit](/The-Haply-Development-Kit) - Hardware Kit
2. [Software Setup](/Software-Setup) - Instructions and links for installing the Arduino IDE and Processing
3. [Hello Wall](/Hello_Wall) - Running your first Haptic Demo


### 4. FAQ
#### Hardware
  - Q: When I run my demo, I don't feel any force feedback. What do I do?  

    A: Check power! If your demo is running (i.e. you can see the sketch working on screen), but aren't feeling any force it is likely that the motors aren't supplied with power to put out any force. So check the power connection to the motors - power should run from a wall outlet to the 12V power adaptor on the board.

  - Q: It seems like one of the arms on my Haplet isn't working, like when I move it the on-screen avatar doesn't move. What's wrong with my device?

    A: The arms of the Haplet could possible come a little bit loose - but fear not! We supply a small Allen Key in the kit - it will fit right into the set screw at the base of the motors where the 3D printed arms attach. Make sure the arms are all lined up, and tighten them. Be sure not to overtighten!  

    [Consider checking out our documentation on kit assembly](https://github.com/HaplyHaptics/Getting-Started/tree/master/The-Haply-Development-Kit), part B to see how the arms work.

  - Q: My avatar is moving backwards! When I move the end effector up it goes down, and vice versa. Help me!  

    A: You've attached the right motor to the wrong port! Or is it wrong motor to the right port? In any case, try switching the cables attaching from the Haply board to the motors around.

    [See our documentation on kit assembly](https://github.com/HaplyHaptics/Getting-Started/tree/master/The-Haply-Development-Kit), part F, to see how the motors should be attached to the board. That said, there are only two possible configurations so you can probably figure out the correct configuration pretty easily 😝

  - Q: One of the parts of my Haplet is broken! What now?  

    A: If one of the 3D printed parts is broken, contact us - we'll send you the .stl file so that you can reprint it! If another part broke or you don't have access to a 3D printer, contact us and we'll send you a replacement part.

#### Software

  - Q: When I try to run a sketch in Processing I get a "COM PORT NOT ASSIGNED" error, nothing I just see a gray screen, or the sketch runs but when I move my Haplet nothing happens.  How do I fix this?  

    A: The COM port is not assigned correctly! You'll have to look at the COM port assignment with the Processing sketch. See the Hello_Wall example "Setting up the Sketch" section for how to do this!

  - Q: I want to dig further into making my own sketches. Where should I look?  

    A: There are two primary places to find documentation on how to make Processing sketches with the Haplet. See the [Haply API documentation](https://haphub.github.io/hAPI_Fisica/) for physics engine specific functions, and the [Processing Reference Library](https://processing.org/reference/) for functions within Processing functions!

  - Q: When I move my device the end effector starts to shake around a lot! What's happening?  

    A: It is likely that either the stiffness is too high or the dampening of the avatar is too low! See the [Haply documentation on the avatar virtual coupling](https://haphub.github.io/hAPI_Fisica/class_h_virtual_coupling.html) to try to lower or raise coupling stiffness or damping values

  - Q: My device isn't working and I checked all the questions above! What now?  

    A: Try a full device reset; it happens from time to time that a full power cycle is the solution. Re-flash the Haply board, close and re-open Processing, and if that doesn't work try restarting the computer. If that doesn't work, send us your code and we'll have a look at it!

### 5. What Next?
You've finished the introduction to the Haplet! Congratulations. If you're still getting to know the Haplet and haptics, we recommend you have a look at the demos in the [Java API](https://github.com/HaplyHaptics/Haply-API-Java). If you're a more experienced user and know what you are looking for, go back to our [Home Page](https://github.com/HaplyHaptics)) and poke around some of our other repositories. Let us know if you have any questions/ concerns/ ideas, and happy Hapletting!
