# Dino Park Totem Calculator 🦖
A lightweight Python tool designed to automate the calculation of resources needed to complete "Totems" in the Dino Park game. It helps players track their progress and identifies exactly how many level 1 units are missing for each dinosaur.

## 🚀 Features
**Automated Calculations:** Converts various dinosaur levels (1-6) into base units (Level 1) using pre-defined balance rates.
**Collection Filtering:** Skips dinosaurs that already have a "Golden Chest" (completed status).
**Summary Report:** Generates a clean, readable list of all dinosaurs that still require attention.
**Clean Code Architecture:** Built using a modular approach with a dedicated calculation engine and a main controller.

## 🛠️ Technical Stack
**Language:** Python 3.x
**Concepts used:** Functional programming (def main(), calculate_missing())
- Data structures (Nested Lists & Dictionaries)
- Logic flow control (Loops, Conditionals)
- Clean Code principles (Snake_case, Type-hinting intent)

## 📋 How It Works
The script iterates through a database of dinosaurs. For each dino without a golden chest, it prompts the user to input the current quantities of units at each level.

**Conversion Logic:**
- Level 6 = 32 units
- Level 5 = 16 units
- Level 4 = 8 units
- ...and so on.

The target for a full totem is 63 units.

## 💻 Installation & Usage
**Clone the repository:**

```Bash
git clone https://github.com/YOUR_USERNAME/dino-park-calculator.git
```
**Run the script:**

```Bash
python dino_calculator.py
```

## 📈 Roadmap
[ ] Add try...except blocks for input validation (Error handling).

[ ] Implement data persistence (Save/Load from JSON file).

[ ] Add a Graphical User Interface (GUI) or a web-based dashboard.
