## T-1000

# Components:

- Arduino Uno
- 2 DC motors + L298N motor driver
- 2–5 IR line sensors 
- Chassis with wheels
- Power supply (battery pack)

# Wiring Overview:

1. IR Sensors:

- Connect VCC → 5V, GND → GND
- Output → Arduino digital pins (e.g., D2, D3, D4 for 3 sensors)

2. Motors via L298N:

- Motor A: IN1 → D8, IN2 → D9
- Motor B: IN3 → D10, IN4 → D11
- ENA/ENB → PWM pins for speed control (D5, D6)

3. Power:

- Motors powered via battery → L298N motor power (12V typical)
- Arduino powered via USB or voltage regulator
