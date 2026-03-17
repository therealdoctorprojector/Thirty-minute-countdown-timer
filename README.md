Thirty minute countdown timer.

If you have ever needed to know when half an hour has passed, this project is for you.
When you turn this device on it will:
Start a countdown timer for 30 minutes.
Show the time remaining.
After 30 minutes a speaker will make a continuous sound until you turn the device off.

The files provided should give you everything you need to make your own timer.
Note that some skill and knowledge are required to make this.

Files:
1. Software source code.
2. Bill Of Materials.
3. PCB design files.

General notes on the software:
1. The software was developed and tested using the Arduino IDE.
2. The thirty minutes has been hard-coded in the software, but you are welcome to change that number and re-compile the software.
3. You can add extra features to the software as you see fit.

General notes on the Bill Of Materials:
1. Prices on the parts are estimates only.
2. There are many variants on the OLED display, in terms of pin count, pin assignments and variations in the size and hole spacing.
3. The switch must be a mechanical latching type.

General notes on the PCB:
1. All through-hole components for ease of soldering.
2. AA batteries are the preferred power source. With some minor adjustments you could use a CR123 lithium battery, or a CR2032 lithium coin cell. You are encouraged to change the PCB design to accommodate the relevant battery holders.
3. The AA battery holder is a widely-copied design “Keystone 2462”, this should give you the correct pin-spacing to fit.
4. I don’t recommend it but you can solder the display board to the main PCB.
5. You are welcome to substitute a surface mount ATTiny85 by making the relevant changes to the PCB. I may generate a revision of the PCB which can be populated with either the 8 pin DIP or the 8-SOIC version.
6. An ICSP header is included on the PCB. No need to fit a 3x2 pin header if you use the Sparkfun PoGo adapter.
7. M3 clearance holes in each corner for fitting the PCB in an enclosure. I would encourage 3D printer users to share a simple design for a suitable case.
8. M2 clearance holes provided to support the OLED display.
