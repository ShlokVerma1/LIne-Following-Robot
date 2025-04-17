# Arduino Line Following Robot

This is a basic **Line Following Robot** project using **Arduino**. The robot uses two infrared (IR) sensors to detect the path and control the motors accordingly to follow a black line on a white surface or vice versa.

## 🚀 Features

- Detects line using two IR sensors (Left Sensor `LS` and Right Sensor `RS`)
- Moves forward, turns left/right, or stops based on sensor input
- Controls two motors using 4 digital output pins

## 🧰 Hardware Used

- Arduino UNO (or any compatible board)
- 2 IR Sensors
- 2 DC Motors with motor driver (like L298N or similar)
- Motor driver module
- Chassis, wheels, and power supply
- Jumper wires and breadboard (optional)

## 🧠 Working Principle

The robot uses two IR sensors to detect the line:
- **Both sensors ON (HIGH):** Move forward
- **Left ON, Right OFF:** Turn left
- **Left OFF, Right ON:** Turn right
- **Both OFF:** Stop

## ⚙️ How to Use

1. Connect the IR sensors and motor driver to the Arduino as per the pin configuration above.
2. Upload the code using the Arduino IDE.
3. Place the robot on a line track.
4. Power the robot using batteries or USB.
5. Watch it follow the line!

## 📦 Folder Structure

```
/LineFollowerRobot
│
├── LineFollower.ino        # Arduino sketch
└── README.md               # This file
```

## 📜 License

This project is open-source and available under the MIT License. Feel free to use and modify it.

---

Let me know if you’d like a schematic or visual wiring guide added too!
