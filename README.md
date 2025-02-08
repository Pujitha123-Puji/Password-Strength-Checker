**Title of the Project**: Password Strength Checker

**Description of the Project**:
**Overview**:
This program is designed to evaluate the strength of a given password based on certain criteria. It checks for the presence of lowercase letters, uppercase letters, numbers, and special characters, as well as the password's length.

**Features**:
1. Password Length Check: The program checks if the password is at least 8 characters long.
2. Character Type Checks: The program checks for the presence of:
    - Lowercase letters (a-z)
    - Uppercase letters (A-Z)
    - Numbers (0-9)
    - Special characters (@#$%+=!)
3. Password Strength Rating: Based on the checks, the program assigns a strength rating to the password:
    - Very Strong (5/5 checks passed)
    - Strong (4/5 checks passed)
    - Medium (3/5 checks passed)
    - Weak (2/5 checks passed)
    - Very Weak (less than 2/5 checks passed)

**Implementation**:
The program uses Python's built-in re module for regular expression matching. The check_password_strength function takes a password as input and returns a strength score based on the checks. The main function prompts the user to enter a password, calls the check_password_strength function, and prints the password strength rating.
