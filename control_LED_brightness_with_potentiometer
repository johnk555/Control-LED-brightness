#define LED_PIN 11
#define POTENTIOMETER_PIN A1

void setup() {
  pinMode(LED_PIN,OUTPUT);
}

void loop() {
  int potentiometer_Value = analogRead(POTENTIOMETER_PIN);
  int brightness = potentiometer_Value / 4 ;
  analogWrite(LED_PIN, brightness);
}
