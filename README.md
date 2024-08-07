
## BLOG APPLICATION

## Overview

This is a Django-based blog application that allows users to:

- **Signup** and **Login**
- Create, view, and manage blog posts
- Add tags to blogs and search by tags
- Perform full-text search with ranking
- Search using trigram similarity
- Add comments to blog posts and like comments
- Share blog posts via email

## Features

- **User Authentication**: Signup and login functionality.
- **Blog Management**: Create and manage blog posts through Django Admin.
- **Pagination**: Display 5 blogs per page.
- **Tagging**: Add tags to blogs and search based on tags.
- **Full-text Search**: Search blog content with ranking.
- **Trigram Similarity Search**: Search using trigram similarity.
- **Comment System**: Add comments to blogs and like/unlike comments.
- **Email Sharing**: Share blog posts via email.

## Installation

### Prerequisites

- Python 3.x
- PostgreSQL
- pip

### Setup

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Vishnu021198/blog.git
   cd blog
   ```

2. **Create a Virtual Environment**:

   ```bash
   python -m venv env
   ```

3. **Activate the Virtual Environment**:

   - **Windows**:

     ```bash
     env\Scripts\activate
     ```

   - **macOS/Linux**:

     ```bash
     source env/bin/activate
     ```

4. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

5. **Configure Database**:

   Update `DATABASES` settings in `blog/settings.py` with your PostgreSQL credentials.

6. **Apply Migrations**:

   ```bash
   python manage.py migrate
   ```

7. **Create a Superuser**:

   ```bash
   python manage.py createsuperuser
   ```

8. **Run the Development Server**:

   ```bash
   python manage.py runserver
   ```

   Navigate to `http://127.0.0.1:8000` in your web browser.

## Contact

For any questions, please contact [Vishnu Nair](mailto:itsvishnunair02@gmail.com).