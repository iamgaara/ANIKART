# ANIKART

ANIKART is a manga selling shopping website built using Django for the backend and a mix of JavaScript, HTML, CSS, jQuery, and Bootstrap for the frontend.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Resources](#resources)
- [Contributing](#contributing)
- [License](#license)

## Introduction
ANIKART is my first Django project and also my first backend project. It is designed to serve as an online platform for buying manga. The project leverages Django's robust backend capabilities alongside a dynamic frontend crafted with JavaScript, HTML, CSS, jQuery, and Bootstrap.

## Features
- User authentication and authorization
- Manga catalog browsing
- Shopping cart functionality
- Order processing
- Responsive design

## Technologies Used
- **Backend**: Django
- **Frontend**: JavaScript, HTML, CSS, jQuery, Bootstrap
- **Database**: SQLite3 (Django's default database)

## Setup Instructions
This project cannot be directly copied and run on your system without proper setup. Follow these steps to get the project running locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/iamgaara/ANIKART.git
   cd ANIKART
Create a virtual environment and activate it

bash
Copy code
python -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`
Install the required packages

bash
Copy code
pip install -r requirements.txt
Apply migrations

bash
Copy code
python manage.py migrate
Run the development server

bash
Copy code
python manage.py runserver
Open your browser and navigate to

arduino
Copy code
http://127.0.0.1:8000/
Resources
To build this website, I used the following resources:

CodeWithHarry's Django Tutorial in Hindi: YouTube Playlist  https://www.youtube.com/playlist?list=PLu0W_9lII9ah7DDtYtflgwMwpT3xmjXY9
W3Schools Django Tutorial: W3Schools    https://www.w3schools.com/django/
ChatGPT


Contributing
If you would like to contribute to this project, please fork the repository and create a pull request with your changes. Ensure your code follows the existing style and conventions.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Feel free to explore the project, and if you have any questions or run into issues, don't hesitate to reach out. Happy coding!
