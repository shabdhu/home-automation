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
1.	Open play store/ App Store in that search BLYNK and download it or else use this link https://play.google.com/store/apps/details?id=cc.blynk for Android and for IOS https://itunes.apple.com/us/app/blynk-iot-for-arduino-esp32/id808760481?mt=8
2.	After installing open BLYNK app and go to create new user and enter your email and password and click next 
3.	This will let you login then go to new project this opens new menu
4.	There you can enter your project name 
5.	Next important thing is you have to select nodemcu in boards
6.	Then select connection type for your device as Wi-Fi
7.	Then select create project this will create your project for your selected device and communication type
8.	This will send you authentication token to your mail this will help you to communicate with your hardware device(nodemcu).you will be using this authentication token later. So save that email.
9.	Then swipe right to left or click '+' button there you have many features of BLYNK there you have to select button widget and add as many buttons required(if you want to control 4 devices use 4 buttons).
10.	Then select button in the project page this will open button’s setting page there you have to select PIN number as per your connection in your nodemcu.Use pin type DIGITAL and pin number such as D5,D6,D7,D8 etc.
11.	Then select mode as switch.
12.	Click ok at top right this will get you to project page. 
13.	Then select play button at top right in project page to bring the project live.

# 3.Back to Hardware:
1. Enter your wifi credentials(Id Name and password) in the code
2. Enter your blynk authentication token which you obtained while configuring the software. You can also find it in your email.(you can also go to project settings in your mobile app and then you can email or copy the authentication token)
3. Upload the code.

# 4.Controlling your device
1. Configure your buttons in the app to control the digital pins( the pins for which you have designed the circuit and connected the relay channels)
2. Plug in the device and press the buttons to control.
