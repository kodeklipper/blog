# Django Blog

A Django-based blogging platform for creating, managing, and publishing blog posts.

## Features

- Create, edit, and delete blog posts
- Categorize posts with tags and categories
- Comment on posts
- User authentication and management
- Responsive design

## Installation Guide

1. **Clone the repository:**
    ```bash
    git clone https://github.com/duke2sd/django-blog.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd django-blog
    ```

3. **Create a virtual environment:**
    ```bash
    python -m venv venv
    ```

4. **Activate the virtual environment:**
    - On Windows:
        ```bash
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```bash
        source venv/bin/activate
        ```

5. **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

6. **Apply database migrations:**
    ```bash
    python manage.py migrate
    ```

7. **Create a superuser (admin account):**
    ```bash
    python manage.py createsuperuser
    ```

8. **Run the development server:**
    ```bash
    python manage.py runserver
    ```

## Usage Guide

1. **Access the blog at:**
    ```
    http://localhost:8000
    ```

2. **Log in to the admin panel at:**
    ```
    http://localhost:8000/admin
    ```

3. **Use the admin panel to create and manage blog posts, categories, and comments.**

4. **Visit the main blog page to view and interact with posts.**
