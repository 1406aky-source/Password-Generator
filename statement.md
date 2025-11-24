Problem Statement
Create a Python program that generates a random password of user-defined length.
The password should contain a mix of lowercase and uppercase letters, digits, and special characters.

Requirements
Prompt the user to input the desired password length.

Validate the user’s input and ensure the length is a positive integer.

If the input is not numeric or non-positive, prompt the user again.
The generated password must:

Be randomly selected from lowercase, uppercase, digits, and punctuation characters.

Be exactly the length entered by the user.

Display the generated password to the user.

Constraints
Use the string and random Python modules.

The password length should be greater than zero.

All input handling must be robust (no crashes with gibberish/non-numeric input).

Notes
The password is generated randomly and may differ each time.

You should run the script from the terminal or command line.

For better security, consider secrets module instead of random for real-world use