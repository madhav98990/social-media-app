# Django Social Media App

A full-featured social media web application built with Django, enabling users to create profiles, post content, interact through likes and comments, and follow each other.

## Features

- User registration, login, logout, and password management  
- User profiles with editable information and profile pictures  
- Create, edit, and delete posts with text and images  
- Like and comment on posts  
- Follow/unfollow other users  
- Responsive and user-friendly interface using Bootstrap  
- Media uploads handled securely with Django's file system  
- Pagination for feeds and profiles  
- Secure authentication and authorization  

## Technologies Used

- **Backend:** Django (Python)  
- **Frontend:** HTML, CSS, Bootstrap, JavaScript  
- **Database:** PostgreSQL (can be switched to SQLite for development)  
- **Version Control:** Git & GitHub  
- **Deployment:** (Optional) Heroku, AWS, or any preferred hosting platform  

## Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/social-media-app.git
   cd social-media-app

2. **Create a virtual environment and activate it**

bash
Copy
Edit
python3 -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate

3. **Install dependencies**

bash
Copy
Edit
pip install -r requirements.txt
Configure environment variables

4. **Create a .env file  for sensitive info like:**

ini
Copy
Edit
SECRET_KEY=your_django_secret_key
DEBUG=True
DATABASE_URL=your_database_url

5. **Apply migrations**

bash
Copy
Edit
python manage.py migrate

6. **Create a superuser (optional)**

bash
Copy
Edit
python manage.py createsuperuser

7 **Run the development server**

bash
Copy
Edit
python manage.py runserver

8 **Open your browser**

Visit http://127.0.0.1:8000 to see the app in action.


