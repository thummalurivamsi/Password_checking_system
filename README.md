# 🔐 Password-Based Door Lock System using 8051 Microcontroller

This project demonstrates a **password-protected door lock system** built using an **8051 microcontroller** and **4x3 keypad**, with an LCD display for user interaction.

### ✅ Features
- 6-digit password authentication
- LCD feedback for user prompts
- Access granted or denied messages
- DC motor (representing door lock) control
- Buzzer alert on wrong password

### 🔧 Hardware Requirements
- AT89C51 / 8051 Microcontroller
- 16x2 LCD Display
- 4x3 Matrix Keypad
- DC Motor
- Buzzer
- Power Supply
- Pull-up resistors (if needed)

### 🧠 How it Works
1. The system prompts the user to enter a 6-digit password using the keypad.
2. Each keypress is masked on the LCD with an asterisk `*`.
3. If the correct password (`630199`) is entered:
   - Motor runs to simulate door opening.
   - "ACCESS GRANTED" message is shown.
4. If incorrect:
   - Buzzer rings.
   - "PASSWORD WRONG" and "TRY AGAIN" messages are displayed.

### 📁 File Structure
- `main.c`: Contains the full source code for the system
- `README.md`: Project description and hardware setup

### 🛠 Tools Used
- Keil µVision (for writing and compiling)
- Proteus (for simulation)
- 8051 Development Board

![password_checker_output](https://github.com/user-attachments/assets/29ffcaf9-10c9-4f94-bed3-9084adb205df)
