# #240 USB-to-Serial Isolator (Bidirectional)
Protect your USB sockets with this bidirectional USB to Serial isolator

![image](https://user-images.githubusercontent.com/20911308/158415401-74f6c2d8-a469-40e1-b6ad-c1af422779e7.png)  
See video: #240 on YouTube

This project was based on an idea/project by Tim Blythman in the March 2022 edition of Practical Electronics.
More details on this excellent magazine here: https://www.electronpublishing.com/
I have modified the circuit slightly and created a custom PCB for my own use which I share here.

If you have ever pushed more than 5v up the USB VCC line you will know what a mess it can make of your PC or laptop. This also applies if you do something silly to the RX or TX pins on your Arduino. Apart from letting the magic smoke escape from your Arduino you also run the risk of doing the same to the USB chip on your PC or laptop. Ouch.

This circuit allows bidirectional communication between your PC and your Arduino (or other μController) with absolute safety as the only thing going back and forth is infrared light!

You can also communicate with two PCs (or a PC and laptop) by adding more than one of the CP2102 modules; not normally needed when used with a microcontroller but this circuit allows for that!

Components used:  
![PCB CP2102](https://user-images.githubusercontent.com/20911308/158420459-43577589-1c4d-4b29-9714-9f271b5d7b2c.jpg)  
CP2102 USB-to-Serial converter with its in-built 5v to 3v3 converter  

 Gerber Viewers
 
 Intelligent LEvel Crossing Detector from 1985
