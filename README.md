# Django Custome User Registraions and Login 

1. **User Registration**: The project allows users to create new accounts by providing their email address, username, and password. It includes email verification to ensure the validity of the provided email address.

2. **User Login**: Once registered, users can securely log in using their credentials. The project incorporates Django's built-in authentication system to handle user login sessions.

3. **Customization**: The project is designed to be easily customizable. You can extend the user model to include additional fields specific to your application's requirements. It provides a clean and modular codebase that allows for easy modifications and enhancements.

4. **Error Handling**: The project handles common registration and login errors, such as invalid credentials, duplicate usernames, and email address conflicts. It provides informative error messages to guide users through the process.

### Setup Instructions
To clone and install the project, follow these steps:

1. **Clone the Repository**:
   ```
   git clone https://github.com/imhimansu28/registrations.git
   ```

2. **Navigate to the Project Directory**:
   ```
   cd registrations
   ```

3. **Create a Virtual Environment (Optional but Recommended)**:
   ```
   python3 -m venv env
   ```

4. **Activate the Virtual Environment**:
   - For Windows:
     ```
     .\env\Scripts\activate
     ```

   - For Unix or Linux:
     ```
     source env/bin/activate
     ```

5. **Install the Dependencies**:
   ```
   pip install -r requirements.txt
   ```

6. **Apply Database Migrations**:
   ```
   python manage.py migrate
   ```

7. **Start the Development Server**:
   ```
   python manage.py runserver
   ```

8. **Access the Application**:
   Open your web browser and visit `http://localhost:8000` to access the user registration and login interface.
