This is a inalambric power bank,I did it because i always run up of cables and of battery :B 

<img width="1200" height="1600" alt="FLUC CASE" src="https://github.com/user-attachments/assets/3504d746-3b1d-4cad-af11-5a112307cddd" />

components: 
<img width="921" height="5<img width="1200" height="1600" alt="mhcd" src="https://github.com/user-attachments/assets/a96526ab-2292-4d7d-8797-7c3d77d777be" />
<img width="1200" height="1600" alt="usbc" src="https://github.com/user-attachments/assets/d2c1939a-29d1-4069-8fdf-003bf5bc1e7e" />
<img width="1200" height="1600" alt="tx" src="https://github.com/user-attachments/assets/805637ba-d473-4c72-96ab-14aaf68afe81" />
<img width="1200" height="1600" alt="pila" src="https://github.com/user-attachments/assets/1dc17150-fa84-4933-a56e-dfb347c157e8" />

pin ups: 

The MHCD has 6 pins: 3 GND, one 5V OUT, one VIN, and one BAT. 
The USB-C has 4: V, D-, D+ & G. V = VBUS, D- = negative, D+ = positive, G = GND.
Connect and solder the V pin of the USB-C to the VIN pin of the MHCD, and the G pin (GND) to the GND of the MHCD.
Now, connect and solder the push button to the MHCD, from GND to GND and from the positive of the button to KEY MHCD.
On the coil, there are 2 wires. Right above the wires, there should be the symbol (-)(+). Connect the negative of the TX to the GND of the MHCD, 
and the positive to 5V OUT.
Last but not least, the battery: negative to GND and positive to BAT.

CAD :
<img width="1101" height="649" alt="CAD FLUX CERRA" src="https://github.com/user-attachments/assets/a4874beb-f71d-4740-ab89-9459734587ca" />

