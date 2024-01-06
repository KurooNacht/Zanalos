esp 8266 is the one we gonna use for controlling the TFT. the file spotify_buddy.ino is the main file for the tft to connect with the spotify. the file index.h , List_FPIFFS.h and Web_fetch.h are the extended library for the tft spotify also you need to add some library such as 
TFT_eSPI
TJpg_Decoder
ArduinoJson
and dont forget to set the TFT_eSPI user_setup_select.h and make sure that all is comment except <User_Setups/Setup2_ST7735.h>

for the esp32 setup (bluetooth speaker) you need to make platformio file and then u need to replace the main.cpp file from platformio to my main.cpp
