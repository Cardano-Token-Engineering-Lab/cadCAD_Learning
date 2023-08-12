# cadCAD_Learning
A set of exercises leveraging how to utilize cadCAD for modeling dyanimic systems.  

One important note is the utilizng a virtual environment in Python for CadCAD work is strongly recommended.  This is generally a good practice, but there can be clashes between packages needed for other projects. In addition, cadCAD has a PR in that isn't approved to fix issues when using Python 3.10 or greater.  For this reason, the cadCAD repo has been cloned in this repository, with the required fixes to the requirements and setup.py file.  In short, you can clone this repo and locally install cadCAD by following the directions below with no issues regardless of the version of Python you are using or if there are deprecated libraries that are defaulted as requirements.

## Setting up cadCAD environment
1. Install Python Dependencies
Create a Python 3 virtual environment inside the Hacks folder:

```
cd ./cadCAD_Learning/
python3 -m venv venv
```
2. Activate your virtual environment (operating system dependent, works on macOS/Unix OS):

```
source venv/bin/activate
```
3. Install the Python dependencies from requirements.txt file:

```
python3 -m pip install -r requirements.txt
```