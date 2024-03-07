
# Flask App Test

This repository contains a simple Flask application along with unit tests implemented using unittest. The purpose of this project is to demonstrate how to set up continuous integration (CI) using GitHub Actions to automatically run tests whenever a pull request is made to the sub branchs.

# Continuous Integration with GitHub Actions

This project leverages GitHub Actions for continuous integration. Whenever a pull request is made to the main branch, the defined workflow (flask_app_test.yml) is triggered automatically. The workflow consists of the following steps
## steps
Checkout Code: Fetches the latest code changes from the repository.
Setup 
Python: Sets up the Python environment based on the specified version.
Install Dependencies: Installs the required Python dependencies listed in requirements.txt.
Test App Code: Executes the unit tests defined in main_test.py to verify the functionality of the Flask application.
## Demo


