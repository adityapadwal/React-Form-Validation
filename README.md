
# Simple Form Validator using React.js

This project is a simple form validator implemented using React.js with the useState and useEffect hooks. The form validator allows users to input their username, email, and password and performs basic validation to ensure the form data is correctly formatted. No external libraries or packages were used to keep the implementation lightweight and straightforward.

## Key Features
1. Takes 3 Inputs: The form validator collects the following user inputs:
- Username
- Email
-Password

2. Empty Field Error: If any of the three input fields (username, email, or password) is left empty, an error message will be displayed to prompt the user to fill in all the required information.

3. Valid Email Check: The form validator checks the email input using a regular expression (regex) to ensure that it is in a valid email format. If the provided email is not valid (doesn't match the expected email pattern), an error message will be shown to the user.

4. Password Length Validation: The form validator checks the length of the password to ensure it meets the requirements. If the password is less than 3 characters or greater than 10 characters, an error message will be displayed, guiding the user to choose an appropriate password length.

## How to Use

To use the form validator in your React project, follow these steps:

1. Clone the repository
```bash
  git clone https://github.com/adityapadwal/React-Form-Validator.git
```
2. Change directory to the project folder:
```bash 
    cd simple-form-validator
```

3. Install dependencies (Note: There are no external dependencies required for this project):
```bash 
    npm install
```

4. Run the development server
```bash
    npm start
```

5. Access the form validator in your web browser at 'http://localhost:3000'.


## Contributing

Contributions are welcome! If you find any issues or want to improve the form validator, feel free to submit a pull request. Please ensure that your changes adhere to the project's coding conventions and are well-tested.

Please adhere to this project's `code of conduct`.

Thank you for using our simple form validator! We hope it proves helpful in your projects. If you have any questions or feedback, please don't hesitate to reach out. Happy coding!