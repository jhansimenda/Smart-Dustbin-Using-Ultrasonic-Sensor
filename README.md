#  Smart Dustbin Using Ultrasonic Sensor

A touch-free automatic dustbin that opens and closes its lid using an ultrasonic distance sensor and a servo motor, helping maintain hygiene and cleanliness.

---

##  Project Overview

This project uses an ultrasonic sensor to detect the presence of a hand or object near the dustbin. When an object is detected within a defined distance, the Arduino automatically opens the lid using a servo motor. After a few seconds, the lid closes automatically.

This system is ideal for public places, homes, hospitals, offices, and schools to maintain hygiene.

---

##  Key Features

- Touch-free operation  
- Automatic lid opening and closing  
- Improves hygiene  
- Low cost and easy to build  
- Energy efficient  

---

##  Hardware Requirements

| Component | Quantity |
|----------|---------|
| Arduino Uno | 1 |
| Ultrasonic Sensor (HC-SR04) | 1 |
| Servo Motor | 1 |
| Jumper Wires | As required |

---

##  Pin Connections

| Arduino Pin | Connected Device |
|------------|------------------|
| D9 | Ultrasonic TRIG |
| D10 | Ultrasonic ECHO |
| D6 | Servo Signal |
| 5V | VCC (Servo + Sensor) |
| GND | GND |

---

##  Working Principle

1. The ultrasonic sensor continuously measures distance.  
2. When an object is detected within the set range, Arduino triggers the servo motor.  
3. The lid opens automatically.  
4. After a few seconds, the lid closes again.  
5. This process repeats automatically.

---

##  Software Requirements

- Arduino IDE  
- USB Cable  

---

##  Installation Steps

1. Connect components as per the wiring table.  
2. Upload the Arduino code to the board.  
3. Power the system.  
4. Place your hand near the sensor.  
5. The lid will open automatically.

---

##  Adjustable Parameters

| Parameter | Description |
|----------|-------------|
| `distanceLimit` | Detection distance (default 20 cm) |
| `openAngle` | Lid open angle |
| `closeAngle` | Lid close angle |

---

##  Future Enhancements

- LCD display for usage count  
- Solar powered dustbin  
- IoT based monitoring  
- Voice alerts  


