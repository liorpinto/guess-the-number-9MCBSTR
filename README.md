# Guess the Number – Embedded System Game on 9MCBSTR

A number guessing game implemented in Embedded C for the 9MCBSTR development board, using LEDs, LCD display, and analog input from a potentiometer.

## 🎯 Project Overview

The system randomly selects a number within a user-defined range. The player must guess the number using analog input, with feedback provided via LEDs and LCD messages.

### Core Features

- Real-time interaction using GPIOs, ADC, LEDs and LCD (HD44780)
- Range and number of tries are dynamically selected via analog measurement
- Visual feedback with hints ("Too High" / "Too Low") on each guess
- Game ends with win/loss message and reveals the correct number

## ⚙️ Hardware

- **Board:** 9MCBSTR
- **Input:** Potentiometer via ADC (P4.0)
- **Output:** 8 LEDs and 16x2 LCD
- **Language:** Embedded C (bare-metal, no OS)

## 📂 File Structure

- `main.c` – game logic, hardware interfacing, and control flow
- `README.md` – this file
- `project_description.pdf` – full documentation (Hebrew)

## 🚀 Getting Started

1. Flash `main.c` to the 9MCBSTR board
2. Connect LCD and LEDs to GPIO as defined
3. Use potentiometer to set range and guess number
4. Follow instructions on LCD to play

## 👨‍💻 Developers

- [Lior Pinto](https://www.linkedin.com/in/liorpinto)

---

*This project was developed as part of an academic assignment in electrical engineering studies.*
