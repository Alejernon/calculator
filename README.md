# Calculator

A Python 3 calculator used from the Terminal, built step by step in SCCM4910.

## What it will do
Add, subtract, multiply and divide two numbers; display the result.

## How to run it
Run: python3 calculator.py
Enter the first number, operator (+ - * /), then second number.
The program prints Result: followed by the answer.

Sample test: Run chmod +x run.sh, then ./run.sh. Enter 6, *, 7; 
expect Result: 42.0. 
Stop this test using Ctrl+C. The calculator may print KeyboardInterrupt.

Sample test: Activate the supplied SCCM4910 virtual environment using source /opt/python-venv/sccm-4910/bin/activate.
Then, run chmod +x check.sh followed by ./check.sh and immediately after this run echo $?
expected result: Five passing tests, the success message from ./check.sh and exit status 0 from echo $? 
If exit status is 1, some tests have failed. If exit status is 5, no tests were collected
