Function Check_password_strength(password):
   - Good_length: Checks if the password length is at least 9 characters.
   - Uppercase_present: Checks if the password contains at least one uppercase letter.
   - Lowercase_present: Checks if the password contains at least one lowercase letter.
   - Digit_present: Checks if the password contains at least one digit.
   - Special_present: Checks if the password contains at least one special character (from the specified set).

Strength Levels:
   - Very strong: Password meets all criteria (length, uppercase, lowercase, digit, special character).
   - Strong: Password meets length requirement and includes both uppercase and lowercase letter/letters along with atleast one digit or special character.
   - Moderate: Password meets length requirements and includes either uppercase or lowercase letters along with alteast one digit or special character.
   - Weak: Password meets only length requirements along with any one of the other requirements.
   - Very weak: Password does not meet any of the above mentioned scenerios.

Usage:
   - User inputs their password.
   - The script evaluates the password using the check_password_strength function.
   - It prints out the strength level of the password based on the criteria.
