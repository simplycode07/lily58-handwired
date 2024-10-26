### Step 1: Printing the case
after printing and cleaning the case should look like this
![img](../images/3d-printed-case.png)
![img](../images/3d-printed-case-with-switches.png)

### Step 2: Curling the diodes
Curl the legs of diode opposite to the black mark on the diode. You can curl the black end as well, but make sure you dont switch between the two. **Repeat this 58 times**
![img](../images/curled-doide.png)

### Step 3: Adding usb c to the pro micro (this step is optional)
I could not find any Pro micros with usb C and the builtin usb port is prone to breaking, so I bought a usb C breakout board to add usb C to the pro micro
1. solder two copper enamel wires as shown in the image
![img](../images/usbc-step1.png)
2. The two wires we soldered are D- and D+, so we solder them to our usb breakout board
![img](../images/usbc-step2.png)
3. Bridge the jumper J1 next to  the usb port, this shorts the RAW and 5V line, we can be sure (hope) that the device connected to usb will supply 5V

