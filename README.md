SDL_ESP8266_8PixelStrip <BR>
SwitchDoc Labs <BR>
May 8, 2018<BR>


#Software Installation <BR>

This library uses the sxtandard Adafruit NeoPixel library

Recent versions of the Arduino IDE (1.6.2 and later) make library installation super easy via the Library Manager interface. From the Sketch menu, > Include Library > Manage Libraries...  In the text input box type in "NeoPixel". Look for "Adafruit NeoPixel by Adafruit" and select the latest version by clicking on the dropbox menu next to the Install button. Then click on the Install button. After it's installed, you can click the "close" button.

![alt text](http://www.switchdoc.com/wp-content/uploads/2018/05/leds_arduino-library-manager.png)


#Hardware Installation <BR?

To Hook 8 Pixel Strip up to ESP8266:

1) Take a Grove to Female Pin Header Cable

2) Connect Yellow (P1) to GPIO#2 on your ESP8266 (#2 on SDL WeatherPlus board)

3) Connect Red to 3.3V on your ESP8266 (Note:  You can connect this to 5.5V too)

4) Connect Black to GND on your ESP8266


Compile and Run SDL_ESP8266_8PixelStick.ino on your Arduino IDE and watch the lights change<BR>

![alt text](http://www.switchdoc.com/wp-content/uploads/2018/05/IMG_5708.jpg) 

#To Modify

Change the following at the top of the file to use other pins are if you are chaining 8 pixel strips.

<pre>

#define PIN 2

#define NUM_LEDS 8
</pre>

