# Flask Login Form

A beginner-friendly Flask project demonstrating how to create an HTML login form, submit data using the **POST** method, and display dynamic content with Flask and Jinja2.

## Features

* Flask Routing
* HTML Forms
* POST Request Handling
* Reading Form Data with `request.form`
* Dynamic Template Rendering
* Passing Data from Flask to HTML

## Project Structure

```text
project/
│
├── app.py
│
└── templates/
    ├── login.html
    └── welcome.html
```

## How It Works

1. The home page displays a login form.
2. The user enters a username and password.
3. The form sends a **POST** request to `/login`.
4. Flask retrieves the username using `request.form.get("username")`.
5. The username is passed to `welcome.html`.
6. The welcome page displays a personalized greeting.

## Technologies Used

* Python 3
* Flask
* HTML5
* Jinja2

## Run the Project

Install Flask:

```bash
pip install flask
```

Run the application:

```bash
python app.py
```

Open your browser:

```text
http://127.0.0.1:5000/
```

## Learning Objectives

This project helps beginners understand:

* Flask routing
* HTML forms
* GET vs POST methods
* `request.form`
* Reading user input
* `render_template()`
* Passing variables to Jinja2 templates
