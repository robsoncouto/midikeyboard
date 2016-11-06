# midikeyboard
A USB midi keyboard. Based on an Atmega microcontroller.
##Description
This is a simple adaptation from Martin Homuth-Rosemann's work V-USB-MIDI. I modified it to suit my project. His work can be found at http://cryptomys.de/horo/V-USB-MIDI/index.html
This project uses Objective Development's V-USB code to achieve USB MIDI software only communication with a Atmega32 microcontroller. 
##Hardware
I recycled an old casio keyboard for frame and keys. The microcontroller reads the key matrix and sends a suitable MIDI message through USB. The keyboard be either be used with Linux or Windows. Of course, this can be adapted to other microcontrollers and keyboards.

