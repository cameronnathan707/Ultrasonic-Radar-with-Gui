# Ultrasonic Radar with GUI
 This is not my idea and it comes from Dejan Nedelkovski and the tutorial can be found on his website 
 www.HowToMechatronics.com 

 ## Getting Started 
 1. Upload the .ino radar file to your Ardino board of choice.
 2. Connect Servo and Ultrasonic sensor.
 3. Run the .pde file on your computer.

 ## Troubleshooting 
 ###  1. Not uploading to the Board, 
- Make sure the the board is plugged in to the computer.
- Have the right board and COM Port are selected in the editor.
- Try disconnecting the sensors connected to the SDA, SCL pins.
- If that all fails, try to reboot your computer (MAKE SURE TO SAVE ANY CHANGES MADE FIRST).

### 2. Sensors not reading properly
- Check the connections on the sensors to see if anything fell off.
- Make sure the cables are plugged into the right connection on the board. 
- Sensor boards can be poorly labelled so look for a data sheet to double check the necessary connections.  

### 3. .pde not compiling
- This is probably due to the font used, so under tools create a font the one used, "OCRAExtended-30.vlw", is far down in the list.
- Make sure to either change the name in the code or rename the font to match the code, either should work.

### 4. The .pde can't access/run the code 
- Make sure the Arduino Serial is closed.
- Check the font, under not compiling.  

## Parts
### Arduino Uno
- https://www.amazon.ca/Elegoo-Board-ATmega328P-ATMEGA16U2-Arduino/dp/B01EWOE0UU/ref=sr_1_9?dchild=1&keywords=arduino+uno&qid=1623704701&sr=8-9 

### Ultrasonic Sensor and Servo 
Servo might need upgrading to something more powerful.
- https://www.amazon.ca/Ultrasonic-Bracket-HC-SR04-Distance-Helicopter/dp/B07ZCLMLXK/ref=sr_1_1?dchild=1&keywords=servo+and+ultrasonic&qid=1623704674&sr=8-1 
