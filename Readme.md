# Age Calculator Project

## Overview
This project contains two Python scripts:
1. `print(Hellow world).py`: A simple script that prints a name and age.
2. `age_calc_gui.py`: A graphical user interface (GUI) application built with Tkinter to calculate a person's age based on their birth date.

## Files Description

### 1. `print(Hellow world).py`
- **Purpose**: Demonstrates basic Python variable assignment and printing.
- **Functionality**: 
  - Defines a `name` variable set to "Rahul".
  - Defines an `age` variable set to "21".
  - Prints the name and age to the console.
- **Usage**: Run the script using Python to see the output:
  ```bash
  python "print(Hellow world).py"
  ```
- **Output Example**:
  ```
  Rahul 21
  ```

### 2. `age_calc_gui.py`
- **Purpose**: Provides a GUI for users to input their name and birth date to calculate their age.
- **Dependencies**: 
  - Python's `tkinter` library (for GUI).
  - Python's `datetime` module (for date calculations).
- **Functionality**:
  - Creates a window with input fields for name, birth year, month, and day.
  - Includes a "Calculate age" button that computes the user's age based on the current date.
  - Displays the calculated age in the format: "[Name]'s age is [Age]."
  - Adjusts age calculation if the birthday has not yet occurred this year.
- **Usage**: Run the script using Python:
  ```bash
  python age_calc_gui.py
  ```
- **How to Use**:
  1. Enter your name in the "Name" field.
  2. Enter your birth year, month, and day in the respective fields (e.g., 2000, 6, 15).
  3. Click the "Calculate age" button to see your age displayed below.

## Requirements
- Python 3.x
- Tkinter (usually included with Python standard library)
- No additional external libraries required.

## Installation
1. Ensure Python is installed on your system.
2. Download or clone the project files.
3. Navigate to the project directory in your terminal or command prompt.
4. Run the desired script as described above.

## Notes
- The `print(Hellow world).py` file appears to have a typo in its name ("Hellow" instead of "Hello"). Consider renaming it for clarity.
- The `age_calc_gui.py` assumes valid input (e.g., integers for year, month, day). Invalid inputs may cause errors; consider adding input validation for production use.
- The GUI window is fixed at 280x300 pixels and is not resizable.

## Example GUI Usage
- Input:
  - Name: Rahul
  - Year: 2005
  - Month: 10
  - Day: 20
- Output (assuming today is June 18, 2025):
  - "Rahul's age is 21."

## Future Improvements
- Add input validation to handle non-numeric or invalid date inputs in `age_calc_gui.py`.
- Enhance the GUI with better styling or additional features like clearing inputs.
- Fix the filename typo in `print(Hellow world).py`.

## License
This project is for educational purposes and has no specific license.
