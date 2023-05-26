# Firefly
Archival repository for the Firefly Project. Casually referred to as Universal Mainboard within StrathSEDS. It is the spirit successor of SHAMANBoard.

Firefly is ... [TODO]
![render of the PCB](Main.png)

You can use the Outjob files for generating manufacturing files, all of which are included in the JLCPCB folder

# Known Issues
 - QSPI IO2 connected to PE4 not PE3
 - IMU BOOT pin tied low instead of high
 - Payload board I2C pins swapped
 - Umbilical regulator capacitor reversed
 - Umbilical regulator enable pin should be tied to input not output
 - Potential unnecessary use of I2C buses resulting in lack of SWO
 - lack of reverse current protection diode between USB and Vbat
 - lack of hole in the PCB for the GPS antenna
 
# V2 new feature ideas
 - reposition LEDs for better usage of space
 - RPP MOSFET on battery input