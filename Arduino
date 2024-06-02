const int buttonPin = 2; // the number of the pushbutton pin

void setup() {
  Serial.begin(9600);
  pinMode(buttonPin, INPUT);
}

void loop() {
  int buttonState = digitalRead(buttonPin);
  // if the button is pressed send '1' to Processing
  if (buttonState == HIGH)
  {
    Serial.println('1'); // Send '1' followed by a newline
    delay(200); // Delay a little bit to avoid bouncing
  }
}
