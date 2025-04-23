# SecurePass 🔒

A modern password generator and security checker web application that helps you create strong passwords and check if they've been compromised in data breaches.


## Features ✨

- **Password Generator**:
  - Customizable password length (8-32 characters)
  - Option to include/exclude character types:
    - Uppercase letters (A-Z)
    - Lowercase letters (a-z)
    - Numbers (0-9)
    - Symbols (!@#$%^&*)
  - Cryptographically secure random generation
  - One-click copy functionality

- **Password Checker**:
  - Checks passwords against Have I Been Pwned's database
  - Secure SHA-1 hashing (only first 5 characters sent to API)
  - Clear breach status indicators

- **Email Checker**:
  - Direct link to Have I Been Pwned email checker
  - Email format validation

- **Modern UI**:
  - Clean, responsive design
  - Dark mode by default
  - Smooth animations and transitions
  - Tab-based navigation

## Technologies Used 🛠️

- HTML5, CSS3, JavaScript (Vanilla)
- [Have I Been Pwned API](https://haveibeenpwned.com/API/v3)
- Web Crypto API for secure password generation
- Clipboard API for password copying
- Google Fonts (Inter, Fira Code)

## Usage 🚀
 # Generate Password:

   * Select desired password length

   * Choose which character types to include

   * Click "Generate Password"

   * Click on the password to copy it to clipboard

 - Check Password Security:

   * Enter your password in the "Check" tab

   * Click "Check Password" to see if it's been compromised

 - Check Email Security:

   * Enter your email in the "Check" tab

   * Click "Check Email on HIBP" to be redirected to Have I Been Pwned

## Security & Privacy 🔐
   * No passwords are stored or logged - all checks happen client-side

   * Minimal data sent to APIs - only first 5 characters of password hashes are sent

   * No tracking - the app doesn't use any analytics or tracking scripts

   * Open source - fully transparent code that can be audited

   * For email checks, you'll be securely redirected to the official Have I Been Pwned website.




## Acknowledgements 🙏
 - Have I Been Pwned for their excellent security service

 - Troy Hunt for creating HIBP
