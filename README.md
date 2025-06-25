# Django Food Menu App

A Django web application that allows users to register, log in, and manage a list of food items with descriptions, prices, and images. Built for learning and portfolio purposes.

Features
--------

- User registration and login system
- Add, edit, and delete food items
- Upload food item images
- Clean Bootstrap UI

Tech Stack
----------

- Python 3.x
- Django 4.x
- SQLite (default DB)
- Bootstrap (via CDN)

Getting Started
---------------

1. Clone the Repository

   git clone https://github.com/Soham-Kamble/Food-Menu-App.git
   cd Food-Menu-App

2. Create a Virtual Environment

   python -m venv venv
   source venv/bin/activate     # On Windows: venv\Scripts\activate

3. Install Dependencies

   pip install -r requirements.txt

4. Set Up Environment Variables

   Create a `.env` file in the root directory and add:

   DJANGO_SECRET_KEY='your-secret-key-here'

5. Apply Migrations

   python manage.py migrate

6. Run the Development Server

   python manage.py runserver

   Open http://127.0.0.1:8000/ in your browser.

Project Structure
-----------------

mysite/
├── food/            # Food app
├── users/           # User registration app
├── mysite/          # Project settings
├── templates/       # HTML templates
├── static/          # Static files (optional)
├── .env             # Environment variables (not tracked)
├── requirements.txt
└── manage.py

Notes
-----

- `.env`, `db.sqlite3`, and `venv/` should be excluded via `.gitignore`
- Never commit your real secret key

License
-------

This project is open-source and available under the MIT License.

Acknowledgements
----------------

- Django Documentation: https://docs.djangoproject.com/
- Bootstrap: https://getbootstrap.com/
