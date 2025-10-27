🧮 Unit Converter (Python)

A simple, beginner-friendly **Python project** that converts values between different units — such as length, weight, temperature, and more. Built as part of a Python learning roadmap (based on Corey Schafer’s tutorials).

---

## 🚀 Features

* Convert between **common units**:

  * Length: meters ↔ kilometers ↔ miles ↔ feet
  * Weight: grams ↔ kilograms ↔ pounds ↔ ounces
  * Temperature: Celsius ↔ Fahrenheit ↔ Kelvin
* **Error handling** for invalid input
* **Simple CLI interface** (runs in terminal)
* Easily extendable — add new unit types or conversions

---

## 📂 Project Structure

```
unit_converter/
│
├── converter.py          # Core conversion logic
├── main.py               # CLI interface (entry point)
├── conversions.json      # Optional file for storing conversion factors
├── README.md             # Documentation
└── requirements.txt      # Dependencies (if any)
```

---

## ⚙️ Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/unit-converter.git
   cd unit-converter
   ```

2. **(Optional)** Create and activate a virtual environment

   ```bash
   python -m venv venv
   source venv/bin/activate  # for macOS/Linux
   venv\Scripts\activate     # for Windows
   ```

3. **Run the program**

   ```bash
   python main.py
   ```

---

## 🖥️ Usage Example

```
Welcome to the Unit Converter!
Choose a category: length / weight / temperature
> length
Enter value: 5
From unit: kilometers
To unit: miles
5 kilometers = 3.10686 miles
```

---

## 🧩 How It Works

* The main script (`main.py`) asks for:

  1. The unit category (e.g., “length”)
  2. Value to convert
  3. Source and target units
* It uses **conversion functions** in `converter.py` to compute the result.
* The conversion factors can be stored in a **dictionary** or an external **JSON file** for scalability.

---

## 🧠 Learning Goals

This project helps you practice:

* Variables, conditionals, and loops
* Functions and modular programming
* Exception handling (invalid inputs)
* CLI design and user interaction

---

## 🧩 Possible Extensions

* Add GUI (e.g., with `tkinter`)
* Include currency conversions via API
* Support multiple conversions at once
* Add unit testing with `pytest`

---

## 🧑‍💻 Author

[Edwin Koech]
Based on Corey Schafer’s Python Learning Roadmap.
GitHub: [AFRO](https://github.com/AFRO)

