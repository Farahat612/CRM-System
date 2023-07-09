# CRM-System

A simple CRM system web app using Python, Django, and PostgreSQL.

## Project Overview

This project serves as a practice during a learning journey. It allows users to perform various actions such as registration, login, logout, adding records, viewing records, updating records, and deleting records.

## Project Structure

The project directory structure is organized as follows:

- **Root Directory**: Contains the main project files.
    - **dcrm Directory**: Contains project-specific files.
        - `asgi.py`: ASGI configuration for the project.
        - `settings.py`: Project settings file.
        - `urls.py`: URL configuration for the project.
        - `wsgi.py`: WSGI configuration for the project.
    - **website Directory**: Contains the main app files.
        - `admin.py`: Admin configuration for the app.
        - `apps.py`: Configuration for the app.
        - `forms.py`: Forms used in the app.
        - `models.py`: Database models for the app.
        - `tests.py`: Unit tests for the app.
        - `urls.py`: URL configuration for the app.
        - `views.py`: Views and logic for the app.
    - **templates Directory**: Contains HTML templates used in the app.
        - `add_record.html`: Template for adding a record.
        - `base.html`: Base template used by other templates.
        - `home.html`: Template for the home page.
        - `navbar.html`: Template for the navigation bar.
        - `record.html`: Template for displaying a single record.
        - `register.html`: Template for user registration.
        - `update_record.html`: Template for updating a record.
    - `manage.py`: Django's command-line utility for project management.

## Getting Started

To run the CRM system on your local machine, follow these steps:

1. Clone the repository: `$ git clone <repository-url>`
2. Navigate to the project directory: `$ cd <project-directory>`
3. Install the required dependencies: `$ pip install -r requirements.txt`
4. Set up the PostgreSQL database according to the settings in `dcrm/settings.py`.
5. Apply the database migrations: `$ python manage.py migrate`
6. Start the development server: `$ python manage.py runserver`
7. Open your web browser and visit `http://localhost:8000` to access the CRM system.

## Features

- User registration and authentication.
- User login and logout functionality.
- Add new records to the CRM system.
- View existing records in a paginated format.
- Update and edit records as needed.
- Delete unwanted records from the system.

## Usage

- Register a new user account by accessing the registration page.
- Log in using your registered credentials.
- Use the navigation bar to access different sections of the CRM system.
- Add, view, update, and delete records as needed.
- Log out when you're done using the system.

## Contributing

Contributions to this project are welcome. If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch: `$ git checkout -b my-new-branch`
3. Make your changes and commit them: `$ git commit -am 'Add some feature'`
4. Push the changes to your branch: `$ git push origin my-new-branch`
5. Submit a pull request detailing your changes.

## Known Issues or Limitations

Currently, there are no known issues or limitations with this project.

## License

This project is licensed under the [MIT License](LICENSE).
