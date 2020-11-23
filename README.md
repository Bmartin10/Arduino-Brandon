# Arduino-Brandon

Arduino notebook for Chs, Engineering class. 
Arduino is a coding site, to learn, and find new ways to code. 
This will show my progress as a student learning to code. 




# Finite_Led_blinker

# Description
This is the Led blinker for engineering class.

# Code 

"//hello arduino
int counter=0; 
void setup() {
  //put your main setup here, to run once:
  Serial.begin(9600);
  pinMode(13,OUTPUT);
}
void loop()  {
  Serial.println("blink");
  long timestamp=0; //long is a much larger integer
boolean ledstate,low; 
int delaylength=500; //how long between intervals 
digitalWrite(13,HIGH);
delay(500);
digitalWrite(13,LOW);
delay(500);
  
}" 




