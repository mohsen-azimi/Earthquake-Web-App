# Earthquake Web APP

Forked from: https://github.com/rogerkorantenng/Earthquake-alert, 

Changes in global climate change have given rise to subsequent natural crises, this has caused a lot of damage to humans and property. in this project, I decided to build a machine learning model trained on previous earth-quake occurrences to predict future occurrences in the next 5 days

This project contains a folder and two files namely(requirements.txt and main.py). The folder cantains the template index.html

The index.html file serves as the template for the app and is rendered to the flask app through Jinja2

The main.py conatains the actual code 

The requirements.txt contains a list of all python libraries to be installed

The model folder contains the jupyter notebook file which was saved from Sagemaker studio's after training

# How to install requirements and run app

Before running the main.py file its required of you to install all python libraries listed in the requirement.txt file.
To install the python libraries, you first need to install pip, pip is a standard package manager for python

To install pip on windows visit https://www.w3schools.com/python/python_pip.asp 

To install pip on linux vist https://linuxize.com/post/how-to-install-pip-on-ubuntu-18.04/

To install pip on mac visit https://phoenixnap.com/kb/install-pip-mac

After successfully installing pip, we can now use pip to install libraries in the requirements.txt by running the below command in our terminal

sudo pip3 install -r requirements.txt 

After successfully installing all python libraries through pip, you can now run the application

# How to run/start app

Open terminal and navigate to the folder or path where the files are kept and type the code below

sudo python3 main.py, this opens your web browser on localhost and port 88. 

In the case you rceieve an error OSError: [Errno 98] Address already in use, change the port in the last line of the code to your desired port



