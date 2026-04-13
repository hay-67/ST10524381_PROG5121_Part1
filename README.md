# Chat Application - Part 1

## Student Inoformation
- Name: Hailey Bruitnjies
- Student Number: ST10524381
- Module: PROG5121

---

## Project Information
This project is a java-based login system for a chat application. it allows users to register by entering a username, password, and phone number. The system validates the input, and then allows the user to log in using the registered details.

---

## Features

### Username Validation
- Must contain an underscore
- Must not be more than 5 chars long

### Password Validation
- Minimum of 8 chars long
- Must include:
  - A capital letter
  - Number
  - Special Character

### Phone Number Validation
- Validates all user inputs
- Stores user details
- Returns success/failure messages

### User Login
- Checks username + password entered
- Compares with stored user details
- Returns success/failure message


## Classes Used

### MainApp.java
- Hnadles user input + outputs
- Controls flow of program
- Calls methods from Login class

### Login.java
- Contains Validation methods
- Handles registration
- Stores user data

### LoginTest.java
- Contains unit tests using junit
- Tests all validation methods
- Tests login


## Testing

JUnit was used to test the functionlality of the program, and the following were tested:
- Valid and invalid usernames
- Valid and invalid passwords
- Valid and invalid phone numbers
- Successful and unsuccessful login attempts
- Login status messages

## Program Flow
- Starts in MainApp class.
- User is prompted to enter their details to register.
- Input is validated using methods in Login class.
- If all the user inputs are valid, the user details are stored.
- Program then prompts the user to login.
- Login details are then compared with the stored data.
- Success or failure message is displayed.

