# Reverse Mortgage Calculator

## Who Made This?
**Author:** Yonatan Calimeño and Juan Diego

## What Is It and What Is It For?
This project is an application to calculate the monthly payments of a reverse mortgage, considering factors such as the property's value, the property's condition, marital status, the ages of the owner and spouse, and the interest rate.

## How Do I Run It?

### Prerequisites
Make sure you have Python installed on your system. No additional external dependencies are required to run the project.

### Running the Program
To run the program outside of the development environment:

1. Navigate to the folder:
   Once you have cloned the file, open the command prompt (cmd) or Anaconda Prompt, and navigate to the folder where you saved the file, for example:

    ```bash
    cd C:\Users\yonatan\Desktop\language_two\PRACTICE_CLEANCODE-main
    ```

2. Run the main script:
    ```bash
    python src/console/main.py
    ```

## How Is It Made?

### Project Architecture
The project is organized into two main folders:

- **src**: Contains the application's source code.
  - **console**: Contains the main script `main.py` for user interaction.
  - **logic**: Contains the logic for reverse mortgage calculation (`reverse_mortgage.py`).
- **test**: Contains unit tests to validate the functionality of the code.

### Module Organization
- `src/console/main.py`: Main file for user interaction. Collects user inputs and displays the results.
- `src/logic/reverse_mortgage.py`: Contains the logic functions for reverse mortgage calculation, including input validation and payment calculation.

### Dependencies
- `unittest`: Standard Python library for unit testing.

## Usage
To run the unit tests from the `tests` folder, use the following command:

```bash
python test/unit_tests.py

To run the main file:
python src/console/main.py


