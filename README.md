# dbs_app_tool

# Admin Registration Form

This project is a PHP-based admin registration form that uses Bootstrap for styling, SweetAlert2 for alerts, and includes real-time validation with AJAX for username availability.

## Features

- **Bootstrap Styling**: The form is styled using Bootstrap to provide a responsive and modern design.
- **SweetAlert2 Alerts**: SweetAlert2 is used to display alerts for successful registration.
- **Real-time Validation**: The form includes real-time validation for username availability using AJAX.
- **Password Validation**: Passwords must be at least 6 characters long and include an uppercase letter, a number, and a special character.

## Installation

1. Clone the repository to your local machine.
2. Ensure you have a web server with PHP installed (e.g., XAMPP, WAMP, or a live server).
3. Place the project files in the web server's root directory.
4. Import the database schema provided in the `database.sql` file to your MySQL database.
5. Update the database connection details in the `classes/database.php` file.

## Usage

1. Open the registration form in your web browser.
2. Fill in the required fields (First Name, Last Name, Username, Password).
3. The form will validate the input fields in real-time.
4. If the username is available and all fields are valid, click the "Register" button.
5. Upon successful registration, a SweetAlert2 alert will be displayed, and you will be redirected to the login page.

## File Structure

- `index.php`: The main registration form file.
- `classes/database.php`: Contains the database connection and signupUser function.
- `AJAX/check_username.php`: Handles the AJAX request to check username availability.
- `bootstrap-5.3.3-dist/`: Contains Bootstrap CSS and JS files.
- `package/dist/`: Contains SweetAlert2 CSS and JS files.

## Dependencies

- Bootstrap 5.3.3
- SweetAlert2

## License

This project is licensed under the MIT License.
