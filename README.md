# Training_purpose
first_git
// Define the LED pins
#define LED1 2
#define LED2 3
#define LED3 4
#define LED4 5
#define LED5 6

// Delay time in milliseconds
#define DELAY_TIME 500

void setup() {
  // Initialize the LED pins as outputs
  pinMode(LED1, OUTPUT);
  pinMode(LED2, OUTPUT);
  pinMode(LED3, OUTPUT);
  pinMode(LED4, OUTPUT);
  pinMode(LED5, OUTPUT);
}

void loop() {
  // Turn on all LEDs
  digitalWrite(LED1, HIGH);
  digitalWrite(LED2, HIGH);
  digitalWrite(LED3, HIGH);
  digitalWrite(LED4, HIGH);
  digitalWrite(LED5, HIGH);

  // Wait for the specified delay time
  delay(DELAY_TIME);

  // Turn off all LEDs
  digitalWrite(LED1, LOW);
  digitalWrite(LED2, LOW);
  digitalWrite(LED3, LOW);
  digitalWrite(LED4, LOW);
  digitalWrite(LED5, LOW);

  // Wait for the specified delay time
  delay(DELAY_TIME);
}
