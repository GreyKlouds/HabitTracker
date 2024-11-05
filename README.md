# HabitTracker

A C# application I wrote using VS Code.
This is a console based CRUD application to track a habbit specified by the user. C# and SQLite were used to develop this application.

# Given Requirements:

    This is an application where you’ll log occurrences of a habit.
    This habit can't be tracked by time (ex. hours of sleep), only by quantity (ex. number of water glasses a day)
    Users need to be able to input the date of the occurrence of the habit
    The application should store and retrieve data from a real database
    When the application starts,create a sqlite database, if one isn’t present.
    It should also create a table in the database, where the habit will be logged.
    The users should be able to insert, delete, update and view their logged habit.
    Application should handle all possible errors so that the application never crashes.
    Follow the DRY Principle, and avoid code repetition.

# Features:
  The program uses a SQLite db connection to store and read information.
  If no database exists, or the correct table does not exist they will be created on program start.
