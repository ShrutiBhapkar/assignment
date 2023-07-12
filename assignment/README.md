Creation of a Flask Application. 
##To create a Flask application

###Set up a virtual environment
   -Create a new directory for your project.
   -Open a terminal or command prompt and navigate to the project directory.
   -Run the following command to create a virtual environment:
       python -m venv venv

###Activating Virtual Environment

     venv\Scripts\activate

###Installing Flask
   -While inside the activated virtual environment, run the following command:

       pip install flask

###Create a Flask app file:
   -Create a new Python file in your project directory.
   -Open the file in a text editor.
   -Import Flask and create an instance of the Flask class:

          from flask import Flask
          app = Flask(__name__)

###Define routes and views:

   -Decorate functions with @app.route() to define routes for different URLs:

         @app.route('/')
         def home():
         return 'Hello, World!'

###Running the application
    -In your terminal or command prompt, make sure you are in the project directory with the virtual environment activated.
    -Set the FLASK_APP environment variable to your app file's name:

         set FLASK_APP=app.py

    -Run the following command to start the Flask development server:

         flask run

    -The application will start running, and you can access it in your web browser with the help of the URL displayed in the terminal.
