# Py-Reader

This project makes use of pythons `venv` tool. 
This allows us to install all the project dependencies in a virtual environment. This is important as it will cause less issues especially if you have conflicting dependencies on your local machine.

To use venv first ensure python is install.
`python --version` 
for this project we are using python version 3.10.4

if this command returns the correct version, then we can start the virtual environment.

To do this we use `venv` with comes included in this version of python.

create the Virtual Environment.
`python -m venv venv`

activate the virtual environment
`source venv/bin/activate`

You will now be in the python virtual environment. Any packages you install here will be locked to your local version of this environment. 
To exit the virtual environment, run the following command
`deactivate`

while in the virtual environment we can install the project dependencies listed in the requirments.txt
`pip install -r requirments.txt`