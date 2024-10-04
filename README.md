# Personal Expense Tracker

## Introduction

The Personal Expense Tracker is a simple and user-friendly desktop application designed to help users keep track of their daily expenses and manage their budgets effectively. Built using Python with a graphical user interface (GUI) created using Tkinter, this application allows users to record, view, and update their expenses in real-time. The application also supports tracking bank balances and maintaining a to-buy list to help users stay on top of their financial management.

## Key Features
**Expense Recording:** Record daily expenses by inputting details such as the date, item bought, amount, and mode of payment (cash, credit card, Paytm, etc.).

**Bank Balance Management:** Track and update your current bank balance, ensuring you stay within your financial limits.

**To-Buy List:** Maintain a list of items you plan to purchase in the future, with options to add and remove items from the list.

**Expense History:** View a detailed list of all recorded expenses, including date, item bought, amount spent, and payment mode.

**Edit and Delete Entries:** Easily edit or delete any expense entry, ensuring you have complete control over your financial records.

**Clear All Data:** Option to clear all data from the tracker if you wish to reset or start afresh.

**User-Friendly Interface:** A simple and visually appealing interface that makes financial tracking easy for everyone.

## How the Project Works
The application is built using Python and Tkinter for the GUI, with SQLite serving as the database to store all expense and bank balance records. Below is a breakdown of how the main functionalities work:

**-Expense Management:**

Users can add a new expense by entering the date, item bought, amount spent, and the mode of payment.

Each entry is stored in the SQLite database, which keeps a log of all expenses.

**-Bank Balance Tracking:**

The user can set and update their bank balance.

Every time an expense is added, the bank balance is automatically adjusted.

If the expense exceeds the available balance, the system will prompt an error, ensuring the user stays within their financial limits.

**-To-Buy List:**

Users can maintain a list of items they plan to purchase, which is stored in the database.

Items can be easily added or removed from this list.

**-Expense History:**

A detailed view of all expenses is provided, displaying the date, item bought, amount spent, and the mode of payment.

The user can edit or delete entries to keep their records accurate.

**-Data Management:**


The user has the option to clear all data, which resets the expense tracker and bank balance.

## Database Structure

### ExpenseTracker Table:

**-ID:** Auto-incremented unique identifier for each expense.

**-Date:** The date of the expense.

**-ItemBought:** Description of the item purchased.

**-Amount:** Amount spent.

**-ModeOfPayment:** Method used to pay for the expense.

### BankBalance Table:

**-ID:** Primary key with a fixed value of 1 (since only one balance is tracked).

**-Balance:** Current bank balance of the user.

### ToBuyList Table:

**-ID:** Auto-incremented unique identifier for each to-buy item.

**-ItemName:** The name of the item to be purchased.

## Interface:

Image:

![Screenshot 2024-10-04 143731](https://github.com/user-attachments/assets/a5a83406-cef9-47b2-994a-e7e3f0410f67)

Video:



## Future Improvements

**Multi-User Support:** Allow multiple users to manage their expenses on a shared system.

**Expense Categorization:** Categorize expenses into groups (e.g., groceries, entertainment) for better tracking.

**Graphical Reports:** Provide visual reports of spending habits over time.

**Mobile Version:** Extend the application to mobile platforms for on-the-go tracking.

## Conclusion
The Personal Expense Tracker is a powerful yet easy-to-use application that helps you manage your finances efficiently. By providing an intuitive interface and robust functionality, this tool simplifies the process of tracking daily expenses and keeping your budget under control. Whether you're managing your personal expenses or planning future purchases, this tracker provides the features you need to stay organized and financially secure.
