# Home-automation
Home automation using blynk.

# 1.Configuring your hardware:
1. Download Arduino Ide from the link below
https://www.arduino.cc/download_handler.php
2. Connect your NodeMCU to your computer
You need a USB micro B cable to connect the board. Once you plugged it in, a blue LED will start flashing. If your computer is not able to detect the NodeMCU board, you may need to download the driver on [this page](http://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers).
3. Open Arduino IDE
Go to File > Preferences. In the "Additional Boards Manager URLs" field, type (or copy-paste) http://arduino.esp8266.com/stable/package_esp8266com_index.json. Don't forget to click OK!
4. Then go to  Tools > Board > Board Manager. Type "esp8266" in the search field. The entry "esp8266 by ESP8266 Community" should appear. Click that entry and look for the install button on the lower right.
5. Download the blynk library zip file from https://github.com/blynkkk/blynk-library.
6. Once the Zip file is downloaded ,extract it and copy the entire folder to your Documents > Arduino > libraries folder.
7. Restart Arduino IDE.
8. Then go to Tools > Board and select Nodemcu v1.0. 
9. Then go to Tools > Port and select your port.
10. Then go to Tools > Upload speed and set to 115200.
11. Copy the code or open the program if you have downloaded it.( you can download/view the code from this github repo).

# 2.Configuring your software:

# 3.Back to Hardware:
1. Enter your wifi credentials(Id Name and password) in the code
2. Enter your blynk authentication token which you obtained while configuring the software. You can also find it in your email.(you can also go to project settings in your mobile app and email or copy the authentication token)
3. Upload the code.

# 4.Controlling your device
1. 
