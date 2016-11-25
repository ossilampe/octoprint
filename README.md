# octoprint

um per Octoprint ein Ralais zu schalten ist es notwendig dieses richtig anzuschliessen
![Pinout Raspberry Pi3](https://github.com/ossilampe/octoprint/blob/master/RP2_Pinout.png)  


PI VOM STROM TRENNEN!
Das Relais verfügt über folgende Pins:
JD-VCC: 5v+
VCC: 3.3v+
GND: Masse
IN1: Schalter Relais 1
IN2: Schalter Relais 2 
Befindet sich auf dem Relais ein Jumper zwischen JD-VCC und VCC, so MUSS DIESER ENTFERNT WERDEN. Wenn nicht, grillt Ihr euren PI!
Anschluss an den PI folgendermaßen (Relais => PI):
JD-VCC => PIN 2 (5 VDC)
VCC => PIN 1 (3.3 VDC)
GND => PIN 6 (Ground)
IN1 => Pin 29 (WiringPI 21)
IN2 => Pin 31 (WiringPI 22) 
So sieht das dann aus: 
