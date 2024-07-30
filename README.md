# Student Enrollment Django Application

This Django application manages student enrollments, allowing users to add, view, and manage student records.

## Features

- Add new student records.
- View details of enrolled students.
- Simple web interface to manage student information.
  
## Getting Started

These instructions will help you set up the project on your local machine for development and testing purposes.

### Prerequisites

- Python 3.x
- Django
- Git

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name

2. **Create a virtual environment and activate it:**

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`

3. **Install the required packages:**

   ```bash
   pip install django

4. **Run database migrations:**

   ```bash
   python manage.py migrate

5. **Run the development server:**

    ```bash
    python manage.py runserver

6. Open your web browser and navigate to http://127.0.0.1:8000/ to use the application.

## Usage
1. Open the application in your web browser:
   Navigate to http://127.0.0.1:8000/enrollment/register.

2. Enter your credentials:
   Type the details of the studentin the input boxes.

3. Submit the form:
   Click on Register button. It displays "Student registered successfully".

4. Export the Student details in csv or pdf format:
   Navigate to http://127.0.0.1:8000/enrollment/export/csv for csv file.
   Navigate to http://127.0.0.1:8000/enrollment/export/pdf for pdf file.

## Contributing

If you want to contribute to this project, please fork the repository and submit a pull request with your changes. Ensure your code adheres to the project's coding standards.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

Django documentation and
GitHub for hosting the repository
