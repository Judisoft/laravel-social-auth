# Laravel Social Registration and Login using Google

This repository provides a step-by-step guide on how to implement social registration and login with Google in a Laravel application. By integrating Google Sign-In functionality, users can register and log in to your Laravel application using their Google accounts.

## Prerequisites

Before getting started, ensure that you have the following prerequisites:

- A Laravel project set up on your local machine or server.
- Composer installed globally.
- A Google Developer account with a configured project and credentials.

## Installation

Follow these steps to install and configure Google Social Registration and Login in your Laravel application:

1. Clone or download this repository to your local machine.

2. Navigate to the project directory and install the dependencies using Composer:

   ````shell
   composer install
   ```

3. Create a `.env` file in the project root and populate it with the necessary environment variables. Make sure to include the following:

   ````dotenv
   GOOGLE_CLIENT_ID=your_google_client_id
   GOOGLE_CLIENT_SECRET=your_google_client_secret
   GOOGLE_CALLBACK_URL=your_google_callback_url
   ```

4. Generate the application key:

   ````shell
   php artisan key:generate
   ```

5. Run database migrations:

   ````shell
   php artisan migrate
   ```

6. Start the development server:

   ````shell
   php artisan serve
   ```

7. Open your web browser and access the application using the provided URL.

## Configuration

To configure Google Social Registration and Login in your Laravel application, follow these steps:

1. Create a Google Developer account and set up a new project.

2. Enable the Google Sign-In API for your project.

3. Generate the OAuth 2.0 credentials (client ID and client secret) for your application.

4. Configure the authorized redirect URI in your Google Developer Console.

5. Update the `.env` file in your Laravel project with the generated client ID, client secret, and callback URL.

## Usage

To use Google Social Registration and Login in your Laravel application, follow these steps:

1. Navigate to the registration page of your application.

2. Click on the "Sign up with Google" button.

3. You will be redirected to the Google Sign-In page.

4. Enter your Google credentials and grant access to the application.

5. Upon successful registration, you will be redirected back to your Laravel application, logged in with your Google account.

6. To log in with Google, navigate to the login page and click on the "Sign in with Google" button.

7. You will be redirected to the Google Sign-In page. Enter your Google credentials and grant access to the application.

8. Upon successful authentication, you will be redirected back to your Laravel application, logged in with your Google account.

## Contributing

Contributions are welcome! If you have any improvements or suggestions, please create an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- [Laravel](https://laravel.com) - The PHP framework used in this project.
- [Google Sign-In](https://developers.google.com/identity/sign-in/web) - Google Sign-In API documentation.

## Resources

- [Laravel Documentation](https://laravel.com/docs)
- [Google Sign-In API Documentation](https://developers.google.com/identity/sign-in/web)

## Contact

For any questions or inquiries, please contact kumjude09@gmail.com

Happy coding!