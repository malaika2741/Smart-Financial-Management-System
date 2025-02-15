# Smart-Financial-Management-System

Smart Financial Management System includes Python code utilizing ipywidgets for interactive financial management, specifically evaluating loan eligibility based on salary, credit score, and employment status.

Key Details from the Notebook
Uses ipywidgets for interactive UI elements like IntText, IntSlider, ToggleButtons, and Button.
Implements an interactive loan evaluation system, where:
Salary is entered using IntText
Credit score is adjusted via IntSlider
Employment status is selected using ToggleButtons
Clicking the Evaluate Loan button processes inputs and provides a decision.
Logic:
If unemployed → Loan Denied
If salary < 50,000 PKR → Loan Denied
Otherwise, additional conditions (likely based on credit score) decide eligibility.
