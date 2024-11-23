# Social Media Platform

A modern social media platform built with Django, featuring user authentication, posts, comments, and real-time interactions.

## Features

- User Authentication (Register, Login, Logout)
- User Profiles
- Create, Edit, and Delete Posts
- Like and Comment System
- Follow/Unfollow Users
- Real-time Updates
- Responsive Design

## Technologies Used

- Django (Backend Framework)
- Python
- HTML/CSS
- JavaScript
- SQLite (Database)
- Bootstrap (Frontend Framework)

## Installation

1. Clone the repository:
```bash
git clone [your-repository-url]
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Apply migrations:
```bash
python manage.py makemigrations
python manage.py migrate
```

5. Create a superuser (admin):
```bash
python manage.py createsuperuser
```

6. Run the development server:
```bash
python manage.py runserver
```

The application will be available at `http://localhost:8000`

## Project Structure

```
social/
├── manage.py
├── social/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
└── app/
    ├── models.py
    ├── views.py
    ├── urls.py
    ├── forms.py
    └── templates/
```

## Usage

1. Register a new account or login with existing credentials
2. Create and customize your profile
3. Create posts, like and comment on other users' posts
4. Follow other users to see their content in your feed
5. Explore the platform to discover new content and users

## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any questions or feedback, please reach out to [Your Contact Information]
