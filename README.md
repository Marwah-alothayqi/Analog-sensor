# Analog-sensor
Analog Input Pins has continuous output signal There are various types of analog sensors one of these sensors is the  Photoresistors. this project is about the  Photoresistors sensor also known as light dependent resistors (LDR), are light sensitive devices most often used to indicate the presence or absence of light, or to measure the light intensity,in the case of analog its measure the light intensity.

project components
1.photoresistor
2.Arduino Uno
3.Resistor
4.breadboard‬‬ Board
and Hook Up Wires to connect components as in the picture
In the project, the sensor is connected in analog  port  AO , the analog values are displayed on the Serial monitor.

![Screenshot (1079)](https://user-images.githubusercontent.com/108452991/181673667-fb08863a-b658-48ae-a023-ae4c894df510.png)
using the following code 
void setup()
{
  Serial.begin(9600);
  pinMode(A0, INPUT);
}

void loop()
{
  Serial.println(analogRead(A0));
  
}

try it !
https://www.tinkercad.com/things/dePOEVWBnd6



