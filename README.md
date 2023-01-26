# onlineesp8266counter
This project utilizes an ESP8266 microcontroller to create an online automatic counter system. 



Don't forget to replace the parts of the code with your own Firebase or HTTP client information. (If you are going to use an http client, remove the Firebase plugin from the code and install the httpclient plugin.)

"const char* ssid = "userssid";
const char* password = "userpass";
#define FIREBASE_HOST "user.data.firebaseio.com"
#define FIREBASE_AUTH "user.secret.key""

"If you are using the ESP8266 plugin, make sure to add "http://arduino.esp8266.com/stable/package_esp8266com_index.json" to the additional boards manager url in preferences, and then add the esp8266 board from the boards manager and select the NodeMCU 1.0 option."


# Used libray version

Blynk_Esp8266AT_WM by Khoi Hoang version 1.3.0

esp8266 by esp8266 verison 2.4.1 

 ArduinoJson v.5.13.5

Timemaster last  verison 

firebase arduino last version 

The most important here are the "Arduinojson and esp8266" versions, because if you use different versions, you may get the "Error compilando para la tarjeta NodeMCU 0.9 (ESP-12 Module)." error.



