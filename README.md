# Calculator
A python 3 calculator used from the Terminal, built in SCCM4910.
A tool used to answer mathmatical calculations quickly and display answer.

## What it will do
Add, subtract, multiply, and divide two numbers; display the result.

## How to run it
Run: python3 calculator.py
Enter first number, operator (+ - * /), then second number.
The program prints Result: followed by the answer.

Run: python3
in terminal -> ./run.sh
stop with ctrl+c

## Testing
python3
activate SCCM4910 virtual environment -> 
source /opt/python-venv/sccm-4910/bin/activate
python3 -m pytest --version

file: test_calculator.py
in terminal -> python3 -m pytest -v OR ./check.sh 
then: echo $?

expected 5 test results of:
test_add, test_divide, test_subtract, test_multiply, test_divide_uneven
PASSED and exit status (from echo $?) of 0 meaning no failed tests
