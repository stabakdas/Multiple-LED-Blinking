# Multiple-LED-Blinking
# Arduino UNO has been used here to blink Green, Yellow and Red 3 LED will blink in this project.
int led1 = 8;
int led2 = 7;
int led3 = 4;
void setup() {
//pinmode(pin,mode);  // put your setup code here, to run once:
pinMode(8,OUTPUT);
pinMode(7,OUTPUT);
pinMode(4,OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
// turn the LED on (HIGH is the voltage level)
  digitalWrite(led1, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  // turn the LED off by making the voltage LOW
  digitalWrite(led1, LOW);
  
digitalWrite(led2, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  // turn the LED off by making the voltage LOW
  digitalWrite(led2, LOW);
  
  digitalWrite(led3, HIGH);
  delay(1000); // Wait for 2000 millisecond(s)
  // turn the LED off by making the voltage LOW
  digitalWrite(led3, LOW);
  
}
