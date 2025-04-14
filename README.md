# Python-Flask
This repository contains a series of beginner-friendly Flask web applications

**_accessing_forms.py_**

- This Python file creates a basic Flask web application with a simple form.

- The code starts by importing the necessary Flask modules and creating a Flask app using Flask(__name__).

- A route /form is defined that handles both GET and POST requests:

        - When you open the page in the browser (GET request), it loads and shows a form (form.html) with an input field and submit button.

        - When you fill in the form and click submit (POST request), the app gets the username from the form and displays a greeting.
