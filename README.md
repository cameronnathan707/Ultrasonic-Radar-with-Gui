# Ultrasonic Radar with Gui
 This is Not my idea and it comes from Dejan Nedelkovski and the tutorial can be found on his website 
 www.HowToMechatronics.com 

 ## Getting Started 
 1. Upload the .ino radar file to your Ardino board of choice
 2. Connect Servo and Ultrasonic sensor
 3. Run the .pde file on you computer

 ## Trouble shooting 
 ### 1. Not uploading to the Board, 
- Make sure the the board is plugged in to the computer
- Have the right board and COM Port are selected in the editor
- Try disconnecting the sensors connected to the SDA, SCL pins
- If that all fails, try to reboot you computer (MAKE SURE TO SAVE ANY CHANGES MADE FIRST)

### 2. Sensors not reading properly
- Check the connections on the sensors so see if anything fell off
- Make sure the cables are plugged into the right connection on the board 
- Sensor boards can be poorly labelled so look for a data sheet to double check the necessary connections  

### 3. .pde not compiling
- This is probably due to the font used, so under tools create a font the one used, "OCRAExtended-30.vlw", is far down in the list
- Make sure to either change the name in the code or rename the font to match the code, either should work

### 4. The .pde can't access/run the code 
- Make sure the Arduino Serial is closed
- Check the font  
