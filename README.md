// Define the digital pins for the traffic lights
const int RED_LED = 4;
const int YELLOW_LED = 3;
const int GREEN_LED = 2;

void setup() {
  // Configure the LED pins as outputs
  pinMode(RED_LED, OUTPUT);
  pinMode(YELLOW_LED, OUTPUT);
  pinMode(GREEN_LED, OUTPUT);
}

void loop() {
  // 1. GREEN LIGHT ON - 5 seconds
  digitalWrite(GREEN_LED, HIGH);
  digitalWrite(YELLOW_LED, LOW);
  digitalWrite(RED_LED, LOW);
  delay(5000);

  // 2. YELLOW LIGHT ON - 2 seconds
  digitalWrite(GREEN_LED, LOW);
  digitalWrite(YELLOW_LED, HIGH);
  digitalWrite(RED_LED, LOW);
  delay(2000);

  // 3. RED LIGHT ON - 5 seconds
  digitalWrite(GREEN_LED, LOW);
  digitalWrite(YELLOW_LED, LOW);
  digitalWrite(RED_LED, HIGH);
  delay(5000);
}
