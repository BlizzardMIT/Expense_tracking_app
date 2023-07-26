## Introduction
In this Python project, the goal is to build an Expense Tracker app in the command line or terminal. 
The app will allow users to track and categorize their monthly expenses to help them budget for the month.

The project specs for the app are as follows:
1. Users will enter their expenses, which include the expense name and amount.
2. The app will save the expenses to a CSV file.
3. It will then read the file to summarize the expense totals for the month.
4. Users can set a budget for the month, and the app will calculate how much they have left to spend each day.

## Functions
The app will have three main functions:
1. get_user_expense: This function prompts the user to enter the expense name, category, and amount. It presents a list of predefined categories for the user to choose from.
2. write_to_file: This function takes the user's expense information and saves it to a CSV file.
3. summarize_expenses: This function reads the CSV file, calculates the total expenses for each category, and provides a summary of the expenses.
The project also emphasizes the importance of planning before writing code, breaking down the problem into smaller tasks, and using functions to modularize the code. Additionally, it highlights the use of the if __name__ == "__main__": condition to ensure the main function is only executed when running the app directly.

## Saving to a CSV file
The project demonstrates how to implement the get_user_expense function, providing a list of categories for the user to choose from and validating the user's input.

These steps will be implementing the remaining functions (write_to_file and summarize_expenses) to complete the Expense Tracker app.
In this section, the code for an expense tracking application that allows users to add expenses and save them to a file. 

The code walkthrough includes the following key steps:
1. It shows how to get user input for the expense name, amount, and category.
2. It creates an "Expense" class and demonstrate how to use it to create an expense object with the user's input.
3. How to save the expense to a CSV file using the "append" mode so that new expenses are added to the existing file.
4. The code to read the expenses from the file and display them is shown. The file is opened in read mode, and each line is read and processed to create expense objects.
5. I use the "strip" and "split" functions to clean up and extract individual elements (name, amount, and category) from each line of the file.
6. Finally, the code is tested, and the output shows the expenses stored in the file.
Overall, the code walkthrough covers adding, saving, and summarizing expenses in the expense tracking application.


## Summarise
The guidelines outline the process of building an expense tracking app in Python. 
The steps include:
1. Reading and processing expense data from a CSV file.
2. Creating a class to represent individual expenses.
3. Extracting and storing expense information in a list of objects.
4. Summarizing expenses by category and displaying the results.
5. Calculating the total spent, remaining budget, and budget per day.

The app uses file handling, classes, dictionaries, list comprehensions, and string formatting to achieve its functionality. 
It allows users to track their expenses, view expenses by category, and stay within budget by providing daily spending limits. 
The app also demonstrates using special characters to display text in different colors for visual appeal in the terminal.


