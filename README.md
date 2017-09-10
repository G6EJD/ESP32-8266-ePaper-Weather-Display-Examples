# ESP32-8266-ePaper-Weather-Display-Examples

This is self-contained sourcecode, so no external graphic files are required.

To implement the code, choose either the ESP8266 or ESP32 version and connect your display to your processor as for an SPI  device, load the code into your IDE, enter your Weather Underground API key and WiFi credentials (SSID, Password) compile and upload.

SPI pins are found in the source code. Note some ESP32 modules will not allow pins like 5, 19, 21, 22 to be re-defined as the compiler directives override the display driver settings of the required pins. Therefore, I recommend using the GPIO pins I have used. 

Enjoy!
