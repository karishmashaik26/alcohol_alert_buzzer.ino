# alcohol_alert_buzzer.ino
# 🍻 Alcohol Detection Alert System using MQ-3 Sensor

This project uses an MQ-3 alcohol sensor with an Arduino UNO to detect alcohol presence and activate **LED** and **Buzzer** alerts when detected. Ideal for driver safety systems or access control based on breath alcohol content.

---

## 🧰 Hardware Required

- Arduino UNO  
- MQ-3 Alcohol Sensor (Digital Output)  
- 5mm LED  
- Buzzer  
- Resistors (220Ω for LED)  
- Jumper wires  
- Breadboard

---

## 🔌 Pin Connections

| Component       | Arduino Pin |
|----------------|-------------|
| MQ-3 Sensor     | D3          |
| LED             | D9          |
| Buzzer          | D10         |
| MQ-3 VCC/GND    | 5V / GND    |

---

## 🚦 Working

- If **alcohol is detected**:
  - LED turns ON
  - Buzzer sounds
  - Serial Monitor shows `"ALCOHOL detected..."`

- If **no alcohol is detected**:
  - LED & Buzzer remain OFF
  - Serial Monitor shows `"No ALCOHOL detected."`

---

## 💡 Output Sample (Serial Monitor)

```text
1
ALCOHOL detected...
0
No ALCOHOL detected.

