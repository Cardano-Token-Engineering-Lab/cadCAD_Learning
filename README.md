# cadCAD_Learning
A set of exercises leveraging how to utilize cadCAD for modeling dyanimic systems.  

One important note is the utilizng a virtual environment in Python for CadCAD work is strongly recommended.  This is generally a good practice, but there can be clashes between packages needed for other projects. In addition to this, cadCAD does have some additional steps to make it work with Python 3.10 or greater.  There are no issues with Python <= 3.9.X.

Much of the information in this repo has been slimmed down from the cadCAD.Education course and tailored around basic usage of cadCAD and slowly growing to a 

1. Install Python Dependencies
Create a Python 3 virtual environment inside the Hacks folder:

'''
cd ./cadCAD-Hacks/
python3 -m venv venv
'''
Activate your virtual environment (operating system dependent, works on macOS/Unix OS):

'''source venv/bin/activate'''
Install the Python dependencies from requirements.txt file:

'''python3 -m pip install -r requirements.txt'''