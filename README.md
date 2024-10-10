# Birthday Tracker

This project is a simple web application that tracks people's birthdays. Users can add names and birthdays (month and day), and the entries will be stored in a database.

## Features
- Add new birthday entries.
- Display a list of all saved birthdays.
- Input validation to ensure valid month and day.
- Built using **Flask**, **Jinja2**, **Python**, **HTML**, **CSS**, and **SQLite3**.

## How It Works
- Users input a name, month, and day, which are then stored in an SQLite database.
- The application checks if the month is between 1 and 12, and if the day is between 1 and 31.
- All stored birthdays are displayed on the main page.
