# Task1-on-Electrical-Power-and-Electronics-Engineering

# Task: Control 4 Servo Motors Using Arduino (Tinkercad)


## Project Overview

This project was developed using **Arduino Uno** and **Tinkercad Circuits**.

The objective is to control four servo motors to perform two sequential actions:

1. Move all four servo motors using the **Sweep** motion for **2 seconds**.
2. After two seconds, stop all motors and hold them at **90°**.

---

# Components Used

- Arduino Uno
- 4 × Servo Motors
- Small Breadboard
- Jumper Wires
- Tinkercad Circuits

---

# Wiring Connections

## Arduino to Breadboard

- Arduino **5V** → Breadboard **Positive (+) Rail**
- Arduino **GND** → Breadboard **Negative (-) Rail**

This allows all servo motors to share the same power and ground connections.

---

## Servo Connections

| Servo Motor | Signal Pin | Power | Ground |
|-------------|------------|--------|--------|
| Servo 1 | D3 | 5V Rail | GND Rail |
| Servo 2 | D5 | 5V Rail | GND Rail |
| Servo 3 | D6 | 5V Rail | GND Rail |
| Servo 4 | D9 | 5V Rail | GND Rail |

---

# Working Steps

### Step 1

Create a new circuit in Tinkercad.

### Step 2

Add the following components:

- Arduino Uno
- Small Breadboard
- Four Servo Motors

### Step 3

Connect Arduino 5V to the positive rail on the breadboard.

### Step 4

Connect Arduino GND to the negative rail on the breadboard.

### Step 5

Connect every servo motor:

- Red wire → Positive rail (+)
- Brown/Black wire → Negative rail (-)
- Signal wire → Arduino digital pin

### Step 6

Connect the signal wires as follows:

- Servo 1 → Pin 3
- Servo 2 → Pin 5
- Servo 3 → Pin 6
- Servo 4 → Pin 9

### Step 7

Write the Arduino code using the Servo library.

### Step 8

Run the simulation.

The motors first perform the Sweep movement for two seconds, then move to 90° and remain fixed.

---

# Program Logic

1. Include the Servo library.
2. Create four servo objects.
3. Attach each servo to its digital pin.
4. Record the starting time using `millis()`.
5. Execute the Sweep motion for exactly two seconds.
6. Move all servo motors to 90°.
7. Keep them fixed at that angle.

---

# Expected Output

- All four servo motors start moving together.
- The motors perform a Sweep motion for two seconds.
- After two seconds, every motor stops at 90°.

---
# Opening the Project

This project is available on Tinkercad through the shared project link.

To open and test the project:

1. Open the Tinkercad project using the following link:

   **Project Link:**
   
  https://www.tinkercad.com/things/3HSlfJO0BRY/editel?returnTo=%2Fdashboard&sharecode=c_QJsOk_RFkSIqGluxzmt632wtR49dHIzO7BxZQ7aFg

3. Sign in to your Tinkercad account if required.

4. Open the circuit.

5. Click **Start Simulation** to run the project.

6. The four servo motors will perform the Sweep movement for two seconds, then stop and hold at **90°**.


# Possible Problems

- Incorrect wiring of the signal wire.
- Forgetting to connect the Breadboard to Arduino 5V and GND.
- Wrong digital pin numbers in the code.
- Servo motors connected with reversed power wires.
- Using a digital pin different from the one specified in the program.

---

# Future Improvements

- Control each servo motor independently.
- Change the sweep speed using variables.
- Add push buttons to start or stop the motion.
- Control the servo motors using Bluetooth.
- Display the servo angle on an LCD display.
- Add sensors to control the servo motors automatically.

---

# Conclusion

The project successfully controls four servo motors using Arduino Uno in Tinkercad. The motors perform the Sweep motion for two seconds and then stop at 90°, meeting all the required task objectives.
