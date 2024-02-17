# Password Manager

This Password Manager is a simple desktop application built with Python and Tkinter. It allows you to generate secure passwords, save them alongside your usernames and websites, and retrieve them whenever needed. The passwords are stored locally in a JSON file for easy access and management.

Features

Generate Password: Create a strong, random password that combines letters, numbers, and special characters. The generated password is automatically copied to your clipboard for immediate use.
Save Password: Store your website, username, and generated password. Before saving, the application checks to ensure no fields are left empty.
Find Password: Retrieve stored passwords by entering the associated website. If the website exists in the database, the application will display the username and password.
User Interface: A user-friendly GUI built with Tkinter, featuring input fields for the website, username, and password, along with buttons to generate passwords, save information, and search for stored passwords.
How to Use

Start the Application: Run the script to open the Password Manager GUI.
Generate a Password: Click on the "Generate Password" button to create a new password. The password will be shown in the password field and copied to your clipboard.
Save Information: Enter the website and your username/email. The password field can be filled manually or with the generated password. Click "Add" to save the data to data.json.
Retrieve Information: To find a password, enter the website and click "Search". If the website is in the database, the application will display the username and password.
