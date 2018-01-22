# Alexiares_HPF
This repository contains the High Pass Filter project of the OpenHPSDR Alexiares frontend

This work is protected by the TAPR Open Hardware Licence https://www.tapr.org/ohl.html

Original work by Graham Haddock, KE9H and Phil Harman, VK6APH.

for more informations, please refer to 

https://wiki.electrolab.fr/Projets:Lab:2017:Peripheriques_Angelia

3D image of the board are stored on this repo

HPF_top.jpg

HPF_bottom.jpg

Bom is available in CSV format

A separate BOM in XLS format is dedicated to filter capacitors

Note that ALL filter caps must be C0G or at least NP0 quality

Schematics, pcb design, modules and libs are in Kicad format

Gerber files are fully compatible with Protel 4.6 format

Board's dimensions are oversized to fit the 5x10 and 10x10cm size of all board of the Hermes project under Kicad:

* Alexandrie (Ἀλεξάνδρεια), Alexiares SPI interface
* Alexi2C ( Ἄλεξις), Alternate Alexiares I2C interface
* Alexiares_lpf (Ἀλεξιάρης) Alexiares low pass filter
* Alexiares_hpf (Ἀλεξιάρης) Alexiares high-pass filter
* Alexiares_Coax_Out (Ἀλεξιάρης ) Alexiares antenna switch boards
* Télémaque (Τηλέμαχος),  SSPA U/V/C°/Refl/FWD sensor for the Mentor board 
* Mentor (Μέντωρ) Micro-controler unit(MCU) and security module controling Telemaque informations
* Ulysse ou Odysseus (Ὀδυσσεύς), medium power reflectometer for the Telemaque/Mentor set
* Themis (Θέμις), low power bidirectionnal reflectometer with pre-distorsion (pure signal) output
* Aiôn (αἰών), 10 MHz low drift, low phase noise clock (general purpose)
* Hébé (Ἥβη), EER control system for high efficiency power amp
