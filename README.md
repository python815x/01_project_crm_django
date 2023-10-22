# CRM_WEBSITE README

## Introduction
This CRM Website Django Project is a simple web application for managing customer records. It includes features like user
registration, login, adding, viewing, updating, and deleting customer records. The project is designed for educational
purposes and as a starting point for a more complex application.

## Installation
To run this project on your local machine, follow these steps:

1. Clone the repository:
   git clone https://github.com/python815x/01_project_crm_django

2. Change directory to the project folder:
   cd 01_project_crm_django

3. Create a virtual environment (optional but recommended):

   python -m venv venv

4. Activate the virtual environment:
   - On Windows:

     venv\Scripts\activate

   - On macOS and Linux:

     source venv/bin/activate

5. Install the project dependencies:

   pip install -r requirements.txt


6. Apply database migrations:

   python manage.py migrate


7. Create a superuser for admin access (you'll be prompted to enter a username and password):

   python manage.py createsuperuser


8. Start the development server:

   python manage.py runserver


## Usage
- Access the web application at [http://localhost:8000/](http://localhost:8000/)
- Use the login and registration features to access the customer record management functionality.
- Add, view, update, and delete customer records as needed.

## Project Structure
- `home/`: Contains the main application code.
- `templates/`: HTML templates for rendering pages.
- `forms.py`: Contains Django forms used in the project.
- `models.py`: Defines the data models for customer records.
- `urls.py`: Defines the URL routing for the application.
- `views.py`: Contains the view functions for rendering web pages.
- `settings.py`: Django project settings.
- `manage.py`: Django management script.

## Contributing
This project is for educational purposes, and contributions are not actively sought. However, if you find any issues or
would like to improve the project, you are welcome to submit a pull request.


## Author
This project was created by python815.

## Acknowledgments
- Thanks to the Django community for providing a robust web framework.

Enjoy using the Django Customer Record Management project!