# CashControl

This code is a GUI-based expense tracker program in Python that uses the PyQt5 library. It has a main window class called ___ExpenseTracker___ which inherits from ___QMainWindow___. In the class constructor ___init___, a 2-column table widget is created using the ___QTableWidget___ class to store expenses and their amounts. The layout of the main window is managed using vertical ___QVBoxLayout___ and horizontal ___QHBoxLayout___. The layout has the table widget, a label to show the total expenses and three buttons to add, remove, and print expenses.

When the "Add" button is clicked, it opens a dialog for the user to input the expense name and amount, and adds this information to the table. When the "Remove" button is clicked, the currently selected row is removed from the table. When the "Print" button is clicked, the expenses and their amounts are written to a text file named "receipt.txt". The total expenses are also written to this text file.

Finally, the program creates an instance of ___ExpenseTracker___ and starts the PyQt5 GUI application, which runs until the user closes the window.
