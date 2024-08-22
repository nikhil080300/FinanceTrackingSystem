# FinanceTracker

## Setting Up Your Development Environment

1. **Create a Project Directory**
   - Create a new folder where you want to store your project files.

2. **Set Up a Virtual Environment**
   - Create a virtual environment with the command:
     ```bash
     virtualenv env
     ```
   - If `virtualenv` is not installed, you can install it using:
     ```bash
     pip install virtualenv
     ```
   - Activate the virtual environment:
     - **Windows**:
       ```bash
       .\env\Scripts\activate
       ```
     - **Mac/Linux**:
       ```bash
       source env/bin/activate
       ```
   - If you encounter access restrictions on Windows, execute:
     ```bash
     Set-ExecutionPolicy Unrestricted -Scope Process
     ```
     Then try activating the environment again.

## Setting Up the Project

1. **Clone the Repository**
   - Use Git to clone the project repository:
     ```bash
     git clone https://github.com/nikhil080300/FinanceTrackingSystem.git
     ```

2. **Navigate to the Project Directory**
   - Change into the project directory:
     ```bash
     cd FinanceTracker
     ```

3. **Install Project Dependencies**
   - Install the required packages listed in `requirements.txt`:
     ```bash
     pip install -r requirements.txt
     ```

## Running the Project

1. **Start the Development Server**
   - Launch the project by running:
     ```bash
     python manage.py runserver
     ```
