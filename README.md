# Virtual-Works
Internship Task 1

# Password Strength Checker

## Overview

This Python program evaluates the strength of a password based on several security criteria, including length, uppercase letters, lowercase letters, numbers, and special characters.

The program classifies passwords into different strength levels and provides suggestions to improve security.

## Features

* Checks password length
* Detects uppercase letters
* Detects lowercase letters
* Detects numeric digits
* Detects special characters
* Classifies password strength
* Provides improvement suggestions

## Technologies Used

* Python 3
* Regular Expressions (re module)

## How It Works

The program evaluates a password using the following criteria:

1. Minimum length of 8 characters
2. At least one uppercase letter
3. At least one lowercase letter
4. At least one number
5. At least one special character

Based on these checks, the password is classified as:

* Weak
* Moderate
* Strong
* Very Strong

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/password-strength-checker.git
```

Navigate to the project folder:

```bash
cd password-strength-checker
```

## Usage

Run the program:

```bash
python password.py
```

Enter a password when prompted.

## Example

Input:

```text
Pass123
```

Output:

```text
Password Strength: Strong
Suggestions to improve security:
- Add at least one special character.
```

## Project Structure

```text
password-strength-checker/
│
├── password.py
└── README.md
```

## Author

Yashwanth Reddy

## License

This project is created for educational and learning purposes.
