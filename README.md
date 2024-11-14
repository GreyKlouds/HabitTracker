# HabitTracker

A C# application I wrote using VS Code.
This is a console based CRUD application to track a habbit specified by the user. C# and SQLite were used to develop this application.

# Given Requirements:

    This is an application which allowws a user to log occurrences of a habit.
    Users need to be able to input the date of the occurrence of the habit
    The application stores and retrieves data from a database
    When the application starts,a sqlite database is created, if one isn’t present.
    The users is  able to insert, delete, update and view their logged habit.
    Application handles all possible errors so that the application never crashes.

# Features:

SQLite database connection

    The program uses a SQLite db connection to store and read information.
    If no database exists, or the correct table does not exist they will be created on program start.

    A console based UI where users can navigate by key entry of the given menu

# Main Menu:
