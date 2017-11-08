        /*Simple_PB_LED_V1   */

//We think this is the code to show which section of the arduino will be taking the energy. In this code it is the D3 and D2

//We are assuming the D3 takes the current directly to the LED
const byte LEDpin = 3;

//The D2 takes the current to the button where the button leads to the button. 
const byte SWITCHpin = 2;


//this means the button is off
byte LEDstate = LOW;


void setup() {
  // put your setup code here, to run once:
  
  //using the D3 to show if the button is being pressed (it will be off) 
pinMode(LEDpin, OUTPUT);
  //using the D2 to get the users input of whether the button is being pressed or not
pinMode(SWITCHpin, INPUT);
 //While the switch pin is running through D2, the light is on ( by dealing with the resistor. When the button is not closed the resistor is at a 1)
digitalWrite(SWITCHpin, HIGH);
}


void loop() {
  // put your main code here, to run repeatedly:
LEDstate = digitalRead(SWITCHpin);
digitalWrite(LEDpin, LEDstate);
}
