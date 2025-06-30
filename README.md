# IOT-HOME-AUTOMATION-SYSTEM

COMPANY : CODTECH IT SOLUTIONS

NAME : VANJARAPU TEJA VARDHAN

INTERN ID : CT04DF1823

DOMAIN : INTERNET OF THINGS

DURATION : 4 WEEKS

MENTOR : NEELA SANTOSH KUMAR


This project demonstrates a simple **Home Automation System** using an **Arduino UNO**, simulated on the **Tinkercad platform**. The objective is to simulate control of home appliances, like lights or fans, using LEDs as indicators. The system is designed to turn devices ON and OFF automatically through Arduino programming, laying the foundation for more complex smart home systems.

The circuit consists of basic components such as **two LEDs (red and yellow)**, **220-ohm resistors**, a **breadboard**, **jumper wires**, and the **Arduino UNO microcontroller**. These components are connected in a way that each LED represents an electrical device that can be switched ON or OFF based on programmed logic.

Tinkercad is an online simulation tool developed by Autodesk. It allows users to create, simulate, and test electronic circuits without needing physical hardware. In this project, Tinkercad played a vital role by providing a virtual breadboard, Arduino board, and a platform to write and upload Arduino code. It enabled testing and debugging of the circuit efficiently, making it very helpful for students and beginners learning about embedded systems.

### **Connections:**

* The **5V pin** from the Arduino is connected to the **positive rail** of the breadboard to power the circuit.
* The **GND pin** is connected to the **negative rail** of the breadboard to complete the circuit.
* A **red LED** is connected to **digital pin 6**, with its cathode connected to ground through a **220-ohm resistor**.
* A **yellow LED** is connected to **digital pin 7**, also grounded through another **220-ohm resistor**.
* Jumper wires are used to make all necessary electrical connections between the Arduino and breadboard.

### **Code Functionality:**

The Arduino code is written to alternate between the two LEDs. In the `loop()` function, the red LED turns ON while the yellow LED remains OFF for one second. Then the red LED turns OFF and the yellow LED turns ON for another second. This cycle continues indefinitely. This simulates how appliances in a smart home might turn ON and OFF in a timed or automated manner.

### **Learning Outcome:**

This project teaches the basic principles of home automation using microcontrollers. It introduces the concept of digital outputs, basic programming in Arduino IDE, and safe circuit building practices. The use of Tinkercad makes it possible to test, visualize, and debug the project without any risk of damaging real components, which is ideal for beginners.

### **Real-Life Application:**

Though this setup uses LEDs for demonstration, the same logic can be expanded to control actual home appliances using **relays**, **sensors**, or **IoT modules** (like Wi-Fi or Bluetooth). Features like mobile control, voice activation, or automated response to environmental conditions can be added in future versions.

In conclusion, this Home Automation System is a foundational project for those interested in smart home technology. It offers hands-on learning with a clear path for scaling up to real-world applications using the same core concepts and hardware.

![Image](https://github.com/user-attachments/assets/af8866fb-978c-46e0-91da-8d531d73471b)

