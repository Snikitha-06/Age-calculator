# Age-calculator

An age calculator is a tool or program designed to determine a person's age or the duration between two dates, typically measured in years, months, and days. Age calculators are commonly used in various applications such as form validation, birthday reminders, and legal compliance systems.

How the Program Works

Input:

The program accepts the date of birth (DOB) as a command-line argument. The expected input format for the date is: dd-MM-yyyy. Example: 25-12-1995.

Validations:

Check for Missing Input: If no input is provided, the program will print an error message and exit. Date Format Check: The input string is split and parsed to check if it follows the correct format. Month Check: Ensures the month provided is between 1 and 12. Day Check: Verifies if the provided day is valid for the given month and year (e.g., February 29th is valid only in leap years). Future Date Check: Ensures the provided date of birth is not in the future compared to the current date.

Age Calculation:

After the date of birth is validated, the program calculates the age by comparing the DOB with the current date. The difference is expressed in terms of years, months, and days.

Output:

The program prints the calculated age in a user-friendly format: Your age is X years, Y months, and Z days. If any error occurs, appropriate error messages are displayed.

This program provides an easy-to-use method to calculate a person's age based on their date of birth. It ensures that the input is valid, performs the necessary checks, and handles errors gracefully. You can use this as a foundation for more complex date-based calculations in Java.
