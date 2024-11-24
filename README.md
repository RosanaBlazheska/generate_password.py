# generate_password.py
**Password Manager **

This is a simple Password Manager application built using Python, Tkinter, and SQLite. 
It allows users to securely store website credentials, generate random passwords, and save them to a local database.
**Features**
Password Generator: Creates strong, random passwords for your accounts.
Data Storage: Stores website names, emails, and passwords securely in an SQLite database.
User-Friendly GUI: A graphical user interface built using Tkinter.
Data Management: Prints all stored data to the console after saving (for debugging purposes).
**Requirements**
_Python 3.x: Ensure Python is installed on your machine.
Tkinter: This comes pre-installed with most Python distributions.
SQLite: Used as the database for storing credentials._

**Installation and Setup**
Clone the repository or download the project files:

bash
Copy code
git clone https://github.com/RosanaBlazheska/generate_password.py.git
cd generate_password.py

**Ensure the required dependencies are installed:**

Python 3.x (Download it from python.org)
Tkinter and SQLite come pre-installed with Python.
Place the logo.png file in the correct location:

Add the logo.png file to the project folder (e.g., in the same folder as the script or in an images folder).
Run the project:

bash
Copy code
python generate_password.py
Usage Instructions
Open the application:

A graphical window will appear.
Enter the website name, email, and password:

You can manually input a password or click Generate Password to create a secure random password.
Save your credentials:

Click the ADD button to save the credentials to the database.
View saved credentials:

The application will print all saved credentials to the console for debugging.

**Project Structure**
_generate_password.py: Main script for the application.
pwmanager_db.db: SQLite database file for storing credentials.
logo.png: Application logo ._
README.md: Documentation for the project.
Future Improvements
Add a feature to view, search, and edit saved credentials within the GUI.
Encrypt saved passwords in the database for added security.
Create a login system to protect the password manager.
