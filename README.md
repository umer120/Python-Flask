# Python-Flask
This repository contains a series of beginner-friendly Flask web applications

**_accessing_forms.py:_**

- This Python file creates a basic Flask web application with a simple form.

- The code starts by importing the necessary Flask modules and creating a Flask app using Flask(__name__).

- A route /form is defined that handles both GET and POST requests:

        -> When you open the page in the browser (GET request), it loads and shows a form form.html, which is present in the templates folder, with an input field and submit button.

        -> When you fill in the form and click submit (POST request), the app gets the username from the form and displays a greeting.

**_accessing_templates.py:_**

- In this program, I had passed a name in the url as /hello/<name> where <name>  -> contains the name which is to be displayed in the hello.html code located in the templates folder

**_flask_application.py:_**

- When you open the app in your browser, it shows a form asking for:
   - First Name
   - Last Name
   - Email
   - Address

- When you submit the form:
   - The data is sent to the server using a **POST** request.
   - Flask processes the data and shows it on a new page i.e. result.html present in templates folder.

- You can go back to the form using the **"Go Back"** link.

