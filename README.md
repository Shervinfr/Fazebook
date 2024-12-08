**Fazebook

Fazebook is a Django-based web application designed as a simplified social networking platform. This project aims to provide basic functionality for user management, posts, and social interaction while serving as an educational resource for those learning web development with Python and Django.
Features

    User Authentication: Sign up, log in, and manage user profiles.
    Social Interactions: Create, edit, and share posts.
    Responsive UI: Optimized for various devices using Django templates and static files.
    Extensible Design: Easily extendable for additional features.

Prerequisites

Before you begin, ensure you have the following installed:

    Python
    Django
    A virtual environment tool like venv or virtualenv
    SQLite (or your preferred database)

Installation

    Clone the repository:

git clone https://github.com/Shervinfr/Fazebook.git
cd Fazebook

Create a virtual environment:

python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

Run database migrations:

python manage.py makemigrations
python manage.py migrate

Start the development server:

    python manage.py runserver

    Access the application:
    Open http://127.0.0.1:8000 in your web browser.

Folder Structure

    core/: Main application with authentication and shared functionalities.
    social_book/: Features for managing user posts and interactions.
    static/: Static files for CSS, JS, and images.
    templates/: Django templates for the frontend.
    manage.py: Django's command-line utility for the project.
