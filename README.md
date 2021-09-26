# MSX1-with-d-ram
MSX1 compatible machine with old fashion D-Ram

Specs:  
Z80  
TMS9918 (composiet out)  
8255  
AY-3-8910  
HM4816 X8 V-Ram  
HM4864 X8 Ram  
74xx  logic IC's  



Tested until version 2.5 
This is version 2.6 should work as I only removed the Opamp for audio out and chanced the Transistor for the (Cassete)relay that
probably nobody uses. (because there is also a jack in and out for the cassete)

What works and tested in version 2.5:
- [x] Boot with MSX-Bios and C-Bios 
- [x] Video Out
- [x] audio out (sound was bad in version 2.5 so removed Opamp in 2.6)
- [x] Joystick ports
- [x] cassete in through 3.5"mm jack
- [ ] cassete out not tested
- [ ] Cassete DIN not tested
- [ ] relay (for Cassete REM) did not switch in version 2.5 (chanced transistor but not tested yet)
- [x] reset
- [X] Keyboard 
- [X] Cartridge Slot 1 and Slot2
- [ ] Printer port not tested

Because there is only a matrix connection for the keyboard I used the keyboard from Sergey Kiselev (github.com/skiselev/omega) to test.
I used the keyboard without de chips on it because they are on the main board and I jumpered on U2 the pins 1-2 and 3-4 and 5-6 and 8-9.
And then connected the wires directly to U1 pin 1-9 and J1 the bottom row.

My own keyboard PCB is ready but I am waiting for the switches to test it.

THE KEYBOARD  
The switches came in and it works fine:  
https://github.com/jojoenco/Keyboard-for-MSX1-with-d-ram

Below a foto of version 2.0 


![IMG_20210726_193931](https://user-images.githubusercontent.com/89305963/130328411-ba4a1808-e9c4-46c7-b1bb-16933eadda58.jpg)
