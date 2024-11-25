
# Django Blog Application  

A feature-rich blog application built using **Django**, **Python**, **PostgreSQL**, **HTML**, **CSS**, and **JavaScript**.  

## Features  
- **Blog Management**:  
  - Create new blog posts.  
  - Save draft posts.  
  - Edit or delete posts.  

- **Comment System**:  
  - Add comments to blog posts.  
  - Approve comments as the post creator.  

- **Text Editor**:  
  - Customize text with options like bold, italic, underline, and links.  

- **Authentication**:  
  - User registration and login functionality.  

- **Portfolio Integration**:  
  - Added links to personal portfolio and projects.  

## Tech Stack  
- **Backend**: Django, Python  
- **Database**: PostgreSQL  
- **Frontend**: HTML, CSS, JavaScript
## Demo
[video](https://youtu.be/KcJoYejCwic)

## Setup Instructions  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/PalthiMalleswari/Django_Blog_Application.git  
   cd blog_project/blog_project/my_blog_site

2. Create a virtual environment:
    ```bash
    python -m venv djnago_blog 
    source djngo_blog/bin/activate  # On Windows: djnago_blog\Scripts\activate

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
4. Apply migrations:
    ```bash
  
    python manage.py makemigrations  
    python manage.py migrate
 5. Run the development server:
    ```bash
    Copy code
    python manage.py runserver  
Open the application at: http://127.0.0.1:8000/
