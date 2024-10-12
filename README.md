# Flask Basic Web Application

This is a simple web application built using HTML, CSS, and Flask. The goal of the application is to demonstrate how to create a basic form, handle user input on the backend using Flask, and display the results back to the user.


## Features

- User input form with fields for **Name** and **Email**.
- Backend processing using Flask.
- Displays submitted form data on a result page.
- Simple CSS styling for a clean interface.

## Prerequisites

- **Python 3.x** installed on your system.
- **Flask** library installed.

## How to Run the Application

1. Clone or download this repository.
2. Navigate to the project directory:
3. Run the Flask application:

4. Open your browser and visit `http://127.0.0.1:5000/` to access the application.

## How It Works

1. The homepage (`/`) contains a form where users can enter their **Name** and **Email**.
2. Upon submission, the form data is sent to the `/submit` route using the `POST` method.
3. The Flask backend processes the data and renders a new page (`/result`) showing the submitted information.

## Customization

- **CSS**: You can modify the `style.css` file in the `static` folder to change the design.
- **HTML Forms**: To add more input fields, edit the `index.html` file in the `templates` folder.
- **Backend Logic**: You can extend the Flask app by adding more routes or handling more complex logic in the `app.py` file.

## Contributing

Feel free to fork this project, open issues, or submit pull requests for any improvements or suggestions.

## License

This project is open-source and licensed under the MIT License.