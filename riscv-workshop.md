# Getting Started with RISC-V, Fedora, and AI
A hands-on workshop

-----------------------------------------------------------------

[BACK to HOMEPAGE](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/README.md)


-----------------------------------------------------------------
![remix](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/fedora_remix_dark_blue_and_white.png) 

![DeepComputing](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/DeepComputing-logo.gif)

## Overview

In this exercise, we will install a new operating system by installing a microSD card that has been previously flashed with an aapropriate image for this hardware based upon Fedora 42 for RISC-V.

## Materials

Your workspace will contain either a DC ROMA II laptop or desktop (both leverage the same motherboard), a freshly flashed microSD card with Fedora 42, along with torx bit screwdriver and a smudger.

![DC Roma II Laptop](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1-start.jpg)

## DEMO One:

In this demo, Matt will walk everyone through flashing the microSD card with the latest image for Fedora 42/DC Roma II.
> Please Note:  You can also follow along the demo with the slide deck.

## DEMO Two:  
In this demo, Matt will walk everyone through the steps required to install the new microSD card into the DC Roma II laptop.
> Please Note:  You can also follow along the demo with the slide deck.

## DEMO Three: (optional)
In this demo, Matt will walk everyone through the steps required to install the new microSD card into the DC Roma II desktop.
> Please Note:  You can also follow along the demo with the slide deck.

## EXERCISE One (A):
Since we have flashed the microSD cards in advance (for time saving measures), we'll jump straight into installation of the microSD card into your laptop. 
> For Desktop Users - go to EXERCISE One (B): 

> Please Note: If at any time during the exercise, you have difficulty or a question - please raise your hand.


## Steps:



### 1. Ensure power OFF
> Power should already be off but if on shutdown the machine either via command line or the Graphical Desktop.
![Power supply, all cords disconnected - POWER is OFF](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1-power-off.jpg)


### 2. Unplug power supply
> Disconnect the USB-C powersupply cable

### 3. Remove all modules from both sides
> While pressing the button between the slots, gently slide the modules outward.
![Remove Modules](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1-release-modules.jpg)


### 4. Unscrew bottom section from the keyboard
> On the bottom of the laptop there are 5 screws. unscrew them with the torx bit.
> Please Note: The screws will NOT come all the way out - this is by design so they do not get lost. 
![Unsecure 5 screws](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1-unsecure-screws.jpg)


### 5. Flip laptop over (open faced)
> Gently flip the laptop over and carefullt open it's screen, laying it flat and open on the table.
![Open flat](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1-open-flat.jpg)


### 6. Use smudger to gently pry up keyboard
> Please Note: You must use extreme caution during this step as it is easy to break the ribbon cable from the keyboard that is attached to the mainboard.
> Use the smudger to gently pry up the keyboard which is also magnetically attached. Do not just rip it up and off but only raise it a few inches. 
![Open Lid](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1-open-lid.jpg)
> Just lift the keyboard high enough to gently disconnect it from the mainboard. Once you have disconnected the keyboard from the mainboard set it aside.
![Open Lid](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1-disconnect-ribbon.jpg)


### 7. Disconnect battery with smudger
> Using the smudger, gently pry the battery connector off.
![Disconnect battery](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1-disconnect-battery.jpg)
> Ensure the battery connector is gently disconnected
![Battery disconnected](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1-batt-disconnected.jpg)

### 8. Use smudger to gently lift the metal bracket holding the microSD card
> Please Note: The card bracket is very fragile. It is on a hinge and should not be totally removed. 
> USE EXTREME CAUTION
> Gentry use the smudger to unlock the card bracket (it will swing upwards but not come off).
![Old microSD](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1-old-microSD.jpg)

![Lift latch](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1-lift-latch.jpg)

### 9. Remove microSD card (if present)
> If there was a microSD card in the slot, please set it aside.
![Replace card](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1-remove-replace-card.jpg)


### 10. Install new Fedora 42 microSD card
> Place the Fedora 42 microSD card in the slot.

### 11. Gently close/secure bracket
> Gently close the bracket and secure the microSD card.
![Close latch](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1-close-latch.jpg)


### 12. Reconnect battery
> Gently reattach the battery connector.
![Reconnect battery](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1-reconnect-battery.jpg)


### 13. Reconnect and replace keyboard
> Carefully, realign the ribbon cable connector and reconnect it. 
![Align connector](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1-reconnect-kb1.jpg)
![Insert connector](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1-reconnect-kb2.jpg)
> Carefully, realign the keyboard in its place.
![Realign keyboard](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1-replace-kb.jpg)


### 14. Close & flip laptop over
> Carefully close the laptop lid and then flip the laptop over laying it flat on the table (screws visible)

### 15. Gently tighten screws
> Gently secure the screws - do not over-tighten them as it can destroy the threading.
![Secure the 5 screws](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1-secure-screws.jpg)


### 16. Replace the modules back to their slots
> Replace all modules back into the slots they were originally in.
![Replace modules](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1-replace-modules.gif)


### 17. Plug-in power supply
> Plug the USB-C power cord back into a USB-C slot.

### 18. TURN ON THE POWER
> Open the laptop up and gently press the power button.
> This is the end of this exercise - do not log into the machine yet.
![First boot](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1-boot.gif)
> ....................
> WELCOME
> to
> Fedora
> on
> RISC-V 
> ....................


--------------------------------------------------------------------------------

--------------------------------------------------------------------------------


## EXERCISE One (B):
Since we have flashed 1TB NVMe drives in advance (for time saving measures), we'll jump straight into installation of the microSD card into your desktop.

> Please Note: If at any time during the exercise, you have difficulty or a question - please raise your hand.

![Cooler master](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1b-cooler-master-login.jpg)



--------------------------------------------------------------------------------



## Steps:


### 1. Ensure power is OFF
> Easily identified by light being OFF

![light off](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1b-power-off.jpg)


### 2. Disconnect USB Hub & USB-C power supply from the case
> Once you have confirmed power is off, disconnect the two USB cables from the case.

![case ready](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1b-case-ready.jpg)


### 3. Remove the case screws
> Carefully remove the case csrews (using the torx #5 bit)

> Be sure to carefully set them aside as they are easily lost.

![screws ID](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1b-screws-defined.jpg)

![screw removal](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1b-case-screws.jpg)



### 4. Use the smudger to pop open the case
> Gently use the smudger to pry open the case.

![smudger](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1b-smudger.jpg)


### 5. Remove/Replace the NVMe drive (or microSD card)
> Unscrew the NVMe drive (if present) and replace it with the updated drive.

![nvme](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1b-nvme-screw.jpg)


### 6. Snap over back in place
> Align the cover and gently snap it back together.

![cover snap](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1b-case-closed.jpg)


### 7. Replace all the case screws
> Using the Torx #5 bit, gently replace all the screws - do not over-tighten as it may cause damage to the case.


![screws to be reset](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1b-screws-defined.jpg)



![replace screws](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1b-case-screws.jpg)


### 8. Reconnect the USB Hub
> In the upper right empty slot - reconnect the USB Hub to the case

![USB-HUB](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1b-USB-hub.jpg)


### 9. Connect KB & Mouse to USB Hub
> Reconnect the USB Keyboard and USB mouse to the USB Hub (if disconnected)

![KB mouse](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1b-USB-connections.jpg)

### 10. Connect the HDMI cable to USB Hub
> Reconnect the HDMI cable to the USB Hub (if disconnected)

![HDMI](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1b-hdmi1.jpg)


![HDMI2](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1b-hdmi2.jpg)

### 11. Reconnect the power supply (USB-C) directly into slot
> Reconnect USB-C Power connection to upper left open slot.

![power reconnect](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1b-power-supply.jpg)


### 12. Boot the system
> Press the power button - light should come on and within a few seconds the system will startup.

![power press](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1b-power-press.jpg)

![light on](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1b-power-light.jpg)

![booting](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1B-riscv-ai-screen.jpg)

----------------------------------------------------------------

![running](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab1b-cooler-master-login.jpg)


> ....................
> WELCOME
> to
> Fedora
> on
> RISC-V
> ....................

