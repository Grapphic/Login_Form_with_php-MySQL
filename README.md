# User Login System

This repository contains a simple user login system implemented in PHP using sessions and Bootstrap for styling.

## Description

The user login system allows users to sign in to their accounts and view a welcome message along with their profile information. It includes features such as:

- Session management to keep users logged in across pages
- Redirecting users to the login page if they are not logged in
- Displaying a welcome message with the user's username upon successful login
- Providing a log out button to allow users to log out of their accounts

## Installation

1. Clone the repository to your local machine:

2. Set up a local web server environment (e.g., XAMPP, WAMP, or MAMP).

3. Place the repository files in your web server's document root directory.

4. Import the included SQL file (`database.sql`) into your MySQL database to create the necessary tables.

5. Update the database configuration in `config.php` with your MySQL credentials.

6. Access the application in your web browser.

## Usage

1. Navigate to the login page (`login.php`).

2. Enter your username and password.

3. Upon successful login, you will be redirected to the home page (`index.php`) and see a welcome message along with your profile information.

4. To log out, click on the "Log Out" button.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.

2. Create a new branch (`git checkout -b feature/new-feature`).

3. Make your changes.

4. Commit your changes (`git commit -am 'Add new feature'`).

5. Push to the branch (`git push origin feature/new-feature`).

6. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
