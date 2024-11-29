Above are the lab tasks I was tasked with throughout the module "COM6033-24/25-Applied Artificial Intelligence"

Some information about the project 

To help build this project, I used tools such as **Python**and **Flask**. I also used a student dataset that I found from a trusted source called the UCI Machine Learning Repository. This dataset uses binary classification to predict whether students will perform well or need assistance.

To display the results, I used 2 HTML pages called index.html and predict.html which are put in a folder called "templates"

I then used a style.css to decorate the pages which can be found in the folder "static\css"
then to connect them all I used Python to combine them all in "app.py"

To develop this project, I used a code editor called Visual Studio Code "https://code.visualstudio.com/download" + python version 3.10.11 "https://www.python.org/downloads/release/python-31011/"

To use my code you will need to have a cloned repository of my code

To build and run my code yourself you will need to create a virtual environment (venv) this is to make sure to make sure no other files are running that could interfere with the code

First you will need to make sure you're in the right location you can do by opening a terminal by selecting Terminal > New Terminal and using the "cd" command to check your in the "Assignment" folder in my case it looks like "C:\Users\Admin\OneDrive\Documents\Uni_work\Year 3\ai antesar\COM6033_Project_Assignment\Assignment

Next, you will need to create the virtual environment (venv) if your using a Windows system the command will be "python -m venv venv" for Mac it will be "python3 -m venv venv" This will add the venv folder in your directory

Now that the venv is created you will need to activate it you can do this with the command for Windows ".\venv\Scripts\Activate" for Mac the command is "source venv/bin/activate"

To check if it is activated successfully your command should see venv at the beginning of the terminal 

You will need then need to install all the required packages such as "flask" Alternatively I have made a file containing all the packages required called "requirements.txt" To install this you can run the command "pip install -r requirements.txt"

Finally, to run the app you will need to type the command called "python app.py"

This is what a successful virtual environment should look like 
*******************************************************************************************************
(venv) PS C:\Users\Admin\OneDrive\Documents\Uni_work\Year 3\ai antesar\COM6033_Project_Assignment\Assignment> python app.py
 * Serving Flask app 'app'
 * Debug mode: on
WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on http://127.0.0.1:5000
Press CTRL+C to quit
*******************************************************************************************************

I built the system with the following:
**Windows 10** - The operating system 
**HTML** - The markup language 
**CSS** - The stylesheet
**Python (version 3.10.11)** - The main programming language
**Flask (version 3.1.0)** - The web microframework used
**pandas (version 1.5.3)** - The main python library i used

Ehsan Riaz - [Leeds Trinity University](https://www.leedstrinity.ac.uk/)

