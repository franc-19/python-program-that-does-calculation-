# python-program-that-does-calculation-

Class Structure: The program uses a LibraryBook class to encapsulate all relevant attributes and methods for managing overdue books. This provides a clean structure to handle multiple books if needed in the future.

Date Calculation: The calculate_days_overdue method computes the difference in days between the return_date and due_date.

Fine Determination: The determine_fine_rate method uses an if...elif...else structure to set the fine rate based on the number of overdue days.

Fine Calculation: The calculate_fine_amount method computes the total fine based on the determined fine rate.

Display Information: The display_info method neatly prints all relevant information regarding the book and its overdue status.

Main Function: The main function handles user input and creates an instance of the LibraryBook class, then displays the results.

Usage:
To run the program, simply execute it in a Python environment. You'll be prompted to enter the Book ID, due date, and return date. The program will calculate and display the fine based on the inputs provided.