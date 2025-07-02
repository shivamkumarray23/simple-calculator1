# simple-calculator

**BASIC GUI CALCULATOR USING PYTHON (TKINTER)**

---

### 1. **INTRODUCTION**

This project is a basic calculator developed using the Python `tkinter` library. It implements a Graphical User Interface (GUI) that allows users to perform simple arithmetic operations: addition, subtraction, multiplication, and division. The calculator is user-friendly and designed with colorful button layouts and intuitive interaction. It is a good example of using Python for building real-world desktop applications with GUI.

The program uses event-driven programming, where button presses trigger specific functions (like adding two numbers). It focuses on user interaction and clean layout design. The core logic is implemented through simple functions, making it beginner-friendly and extendable.

This project lays the foundation for understanding GUI development in Python and can be extended to support more complex mathematical features in the future.

---

### 2. **OBJECTIVE**

The main objectives of this calculator project are:

1. To build a simple, responsive calculator using Python’s `tkinter` module.
2. To understand the event-driven approach in GUI-based applications.
3. To use functions for performing arithmetic operations (add, subtract, multiply, divide).
4. To improve Python programming skills through hands-on interface design.
5. To develop an application that mimics real-life tools with clean structure and reusability.

---

### 3. **SOFTWARE & TOOLS USED**

* **Programming Language**: Python 3.x
* **Library**: `tkinter` (built-in GUI library in Python)
* **IDE**: PyCharm / VS Code / IDLE
* **Platform**: Desktop (Windows recommended)
* **Input Device**: Keyboard and Mouse

---

### 4. **SYSTEM DESIGN**

The system is designed with a simple GUI window using `tkinter`. It includes:

* One **Entry widget** for displaying numbers and results.
* Multiple **Button widgets** for digits (0–9) and operations (+, –, ×, ÷, =, Clear).
* The layout is organized using the `.grid()` geometry manager.
* Button clicks trigger custom functions like `click()`, `add_button()`, and `equal_button()` for operations.

---

### 5. **CLASS DESCRIPTIONS**

This project does **not use classes**, as it focuses on functional programming with GUI. However, the structure is modular and clearly separated by functions:

* `click(num)`: Appends the clicked digit to the display.
* `add_button()`, `subtract_button()`, `multiply_button()`, `divide_button()`: Store the first number and selected operation.
* `equal_button()`: Executes the arithmetic operation.
* `clear()`: Clears the display.

---

### 6. **FEATURES IMPLEMENTED & FUNCTIONAL WORKFLOW**

**Features:**

* Accepts number input via GUI buttons.
* Performs basic arithmetic operations: Add, Subtract, Multiply, Divide.
* Displays results on the same screen.
* Provides a clear/reset functionality.
* Uses `tkinter.Entry` for displaying and editing current inputs.

**Workflow:**

1. User opens the app.
2. Types digits by clicking number buttons.
3. Selects an operation (+, –, ×, ÷).
4. Types the second number.
5. Presses “=” to see the result.
6. Uses “clear” to reset.
### 7. **CONSOLE INTERFACE SNAPSHOT**

This project has **no console interface**. It is entirely GUI-driven using buttons and text fields in a graphical window.

### 8. **SAMPLE INPUT/OUTPUT**

| Action                              | Result Shown              |
| ----------------------------------- | ------------------------- |
| Click 5 → Click `+` → Click 3 → `=` | Output: `8`               |
| Click 9 → Click `/` → Click 2 → `=` | Output: `4.5`             |
| Click 7 → Click `x` → Click 6 → `=` | Output: `42`              |
| Click `clear`                       | Output display is emptied |

### 9. **IMPLEMENTATION**

The calculator is implemented using basic `tkinter` elements:

* **Entry** widget for input/output display.
* **Button** widgets for digits and operators.
* **Global variables** store the current value and chosen operation.
* Functions execute the logic for each operation when buttons are clicked.
* 
### 10. **TESTING & VALIDATION**

* Tested all digit and operator buttons for correct response.
* Division by zero handled safely to avoid crashes.
* Input fields and outputs behave as expected for various inputs.
* GUI layout adjusts correctly when resized.

### 11. **ADVANTAGES**

* Easy to use with a clean interface.
* Introduces GUI programming concepts using Python.
* Uses modular functions for clarity and reusability.
* Encourages hands-on learning with event-driven programming.

### 12. **LIMITATIONS**

* Does not support decimal input currently.
* Only two-number operations at a time (not continuous calculation).
* No error handling for non-numeric input or invalid formats.

### 13. **FUTURE ENHANCEMENTS**

* Add support for decimal and negative numbers.
* Allow chained operations (e.g., 2 + 3 × 4).
* Improve layout with better styling and fonts.
* Add features like square root, percent, memory functions.
* Add themes and light/dark mode toggle.

### 14. **CONCLUSION**

This project demonstrates how a basic calculator can be built using Python’s `tkinter` library. It introduces important concepts in GUI design, event-driven programming, and logical structuring. Though simple, this project helps beginners gain confidence in building real applications and prepares them to handle more advanced projects like GUI databases or scientific calculators in the future.

