const int ledPin = 9;  // Pin 9 is the built-in LED pin on most Arduino boards/

void setup() {
  pinMode(ledPin, OUTPUT);  // Set the LED pin as an output
}

void loop() {
  digitalWrite(ledPin, HIGH);  // Turn the LED on
  delay(1000);  
  digitalWrite(ledPin, LOW);  // Turn the LED off
  delay(500);  
}
