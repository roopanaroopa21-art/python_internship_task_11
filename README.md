Regex Validation System (Python)

A simple Python project that demonstrates how to use Regular Expressions (Regex) to validate user inputs such as email addresses, Indian mobile numbers, and passwords.

📌 Project Objective

This project centralizes validation logic using Python's re module and applies industry-standard regex patterns to validate:

✅ Email addresses

✅ Indian mobile numbers

✅ Strong passwords

It also handles edge cases like empty input and invalid formats.

🛠️ Technologies Used

Python 3.x

re module (Regular Expressions)

📂 Project Structure
regex_validation.py
README.md

🚀 Features

Uses re.fullmatch() to prevent partial matches

Validates email using industry-standard pattern

Validates Indian mobile numbers (supports +91 and 0 prefix)

Enforces strong password rules:

Minimum 8 characters

At least one uppercase letter

At least one lowercase letter

At least one digit

At least one special character (@$!%*?&)

Displays meaningful success/error messages

Organized into reusable functions

🧠 Regex Patterns Used
1️⃣ Email Validation
^[A-Za-z0-9._%+-]+@[A-Za-z0-9.-]+\.[A-Za-z]{2,}$

2️⃣ Indian Mobile Number Validation
^(?:\+91|0)?[6-9]\d{9}$

3️⃣ Password Validation
^(?=.[a-z])(?=.[A-Z])(?=.\d)(?=.[@$!%?&])[A-Za-z\d@$!%?&]{8,}$

▶️ How to Run the Program

Make sure Python is installed.

Save the file as regex_validation.py.

Open terminal or command prompt.

Run the command:

python regex_validation.py


Enter the required inputs when prompted.

🧪 Edge Cases Tested

Empty input

Invalid email formats (missing @, domain, etc.)

Mobile numbers with wrong starting digit

Passwords missing required characters

Partial matches

📘 Learning Outcomes

Understanding regex basics

Using re.fullmatch() for exact matching

Writing reusable validation functions

Handling user input safely

Improving code readability and structure

🔮 Future Improvements

Add username validation

Add GUI using Tkinter

Store validated data in a file

Convert into a web-based validation form

👩‍💻 Author

ROOPA N A
