# lm35-arduino-Library-working-in-proteus-with-hex-file-Running
lm35 arduino Library working in proteus with hex file Running
![lm35 arduino Library working in proteus](https://user-images.githubusercontent.com/112553782/187690008-b4dfdfae-9cb7-48b6-88f9-5fc9b68224b3.png)
#include <LiquidCrystal.h>

LiquidCrystal lcd(7, 6, 5, 4, 3, 2);
void setup() 
{
  Serial.begin(9600);
lcd.begin(20, 4);
 lcd.setCursor(0, 0); 
 lcd.print("WELL COME TO");
 lcd.setCursor(0, 1); 
 lcd.print("WWW.ProteusLibrary.com");
delay(500);
lcd.clear();
}
FULL SIMULATION AND CODE AT  https://proteuslibrary.com/

https://youtu.be/x4HavrHvpNY

