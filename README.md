
# Flask App Test

This repository contains a simple Flask application along with unit tests implemented using unittest. The purpose of this project is to demonstrate how to set up continuous integration (CI) using GitHub Actions to automatically run tests whenever a pull request is made to the sub branchs.

# Continuous Integration with GitHub Actions

This project leverages GitHub Actions for continuous integration. Whenever a pull request is made to the main branch, the defined workflow (flask_app_test.yml) is triggered automatically. The workflow consists of the following steps
## steps
Checkout Code: Fetches the latest code changes from the repository.<br>
Setup Python: Sets up the Python environment based on the specified version.<br>
Install Dependencies: Installs the required Python dependencies listed in requirements.txt.<br>
Test App Code: Executes the unit tests defined in main_test.py to verify the functionality of the Flask application.<br>


# Contributing
Contributions to this project are welcome! Feel free to fork the repository, make your changes, and submit a pull request. Please ensure that your code passes all existing tests and consider adding new tests for any new functionality.
