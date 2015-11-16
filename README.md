# Mortgage-Calculator
Mortgage Calculator
CMPE 277
Lab 1 - Mortgage Calculator
Introduction
This is an individual assignment. You’re going to build a mortgage calculator in this lab. 

Mortgage monthly payment calculation:
Input:
Home value
Down payment
Interest rate
Terms (number of years to pay, must be picked from {15, 20, 25, 30, 40})
Property tax rate
A calculate button triggers the calculation, and a reset button is provided to clear all fields. 

Output:
Monthly payment amount
Total interest paid
Total property tax paid
Pay off date

Formula:
http://www.wikihow.com/Calculate-Mortgage-Payments
To verify that your calculation is correct, you can use the mortgage calculator provided by http://www.mortgagecalculator.org/ as a reference. Please note we do not model PMI (Private Mortgage Insurance); i.e., we assume it is zero.
Functionality
The main screen should consist all the necessary properly labeled input fields for the calculation
Output/error message should be shown when user pressed the calculate button
All input/output fields should be cleared for the next calculation when user pressed the reset button

Device & screen size
We are going to grade the assignment on the Nexus 5 and 10 simulators. You want to check in these simulators to make sure the image and text look properly sized and aligned. We check on Nexus 10 for the bonus point only.
Error handling
Your app must have proper error handling for missing required fields(See the formula) or invalid data type.
Example: Interest rate is mandatory for calculation.

Grading
The assignment is worth 5 points, with 1 bonus point available. The breakdown of the points is as follows:
Correctness 3
User interface design and overall user experience 1.5 (checked on Nexus 5 only)
Error handling 0.5
Bonus point: proper tablet and landscape mode support using two fragments for input and output separately (checked on Nexus 10)



