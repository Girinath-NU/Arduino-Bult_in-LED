# Arduino LED Blinking Project

This project demonstrates how to blink the onboard LED of an Arduino board using simple and beginner-friendly code. It's a great starting point to learn about controlling outputs and using delays in Arduino.

---

## Overview

Blinking an LED is one of the first steps to understanding how to interact with hardware using Arduino. This example uses the onboard LED, which is usually connected to pin 13 on most Arduino boards, to create a blinking effect.

---

## Code Breakdown

Here’s the complete code:

```cpp
void setup() {
  // Configure pin 13 as an output pin
  pinMode(13, OUTPUT);
}

void loop() {
  // Turn the LED on
  digitalWrite(13, HIGH);
  delay(1000); // Wait for 1 second

  // Turn the LED off
  digitalWrite(13, LOW);
  delay(1000); // Wait for 1 second
}
