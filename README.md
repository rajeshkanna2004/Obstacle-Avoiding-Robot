# Obstacle Avoiding Robot 🤖

An Arduino-based autonomous robot that detects obstacles using an HC-SR04 ultrasonic sensor and avoids them by automatically changing direction.

---

## Components Used
- Arduino UNO
- HC-SR04 Ultrasonic Sensor
- L298N Motor Driver Module
- 2 DC Motors
- Robot chassis with wheels
- Battery (9V or 12V)
- Jumper wires

---

## Circuit Connections

### HC-SR04 Ultrasonic Sensor
| HC-SR04 Pin | Arduino Pin |
|-------------|-------------|
| VCC         | 5V          |
| GND         | GND         |
| Trig        | Digital Pin 9 |
| Echo        | Digital Pin 10 |

### L298N Motor Driver
| L298N Pin | Arduino Pin / Connection | Description          |
|-----------|--------------------------|----------------------|
| IN1       | Digital Pin 2            | Motor A input 1      |
| IN2       | Digital Pin 3            | Motor A input 2      |
| IN3       | Digital Pin 4            | Motor B input 1      |
| IN4       | Digital Pin 5            | Motor B input 2      |
| ENA       | +5V                      | Enable Motor A       |
| ENB       | +5V                      | Enable Motor B       |
| VCC       | Battery Positive (9V/12V)| Motor power supply   |
| GND       | Battery Negative & Arduino GND | Common ground   |

---

## Features
- Detects obstacles within ~15 cm
- Stops and turns to avoid collision
- Fully autonomous movement logic

---

## How to Run
1. Build the circuit following the connections above.
2. Upload `obstacle_avoiding_robot.ino` code to your Arduino board.
3. Power up the robot using the battery.
4. Place the robot on a flat surface and observe as it moves forward and avoids obstacles.

---

## Author
**Rajesh Kanna PB**  
