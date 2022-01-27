About - User Registration
A user registration must be implemented. After filling the form data which consist (firstname, lastname, email and password) with validation, an email with a confirmation link should be sent to the user.

1. Problems and findings
Problems
* Configuring the mail response in the project
Findings
* I have used laravel/ui and after ui/auth which consist everything needed to make an authentication.
* For email verification i have used mailtrap for mail testing
2. Time Taken to Complete
The project took 2hours
3. Coding style and standards
the coding style is used was line coding and error control , and the standard of using safe ,secure and portable codes
4. Source code files
Link To Repository

5. Documentation
before starting to run the project , make sure you have mailtrap account in order to check the verification link

Requiments
A. Configuration process
Mailtrap [https://mailtrap.io/]
create your .env file
create your database
.env Mailtrap corresponding data
MAIL_MAILER=
MAIL_HOST=
MAIL_PORT=
MAIL_USERNAME=
MAIL_PASSWORD=
MAIL_ENCRYPTION=
MAIL_FROM_ADDRESS= ('input a valid email(you have provided while configuring the mailtrap) if not it wont work)

B. After run these script:
php artisan migrate
php artisan serve
