# PyCart
### An Ecommerce Web App built using React and Django   
Project Link: https://pycart.herokuapp.com/ 

## Libraries Used : 
### For Frontend
- React (Javascript Framework)
- Redux
- React-Bootstrap
- Axios
- React Router

### For Backend
- Django
- Django Rest Framework
- SimpleJWT for Authentication

### Database
- SQLite (For Development)
- Postgresql (For Production)

## Steps to run the project locally : 

Clone the Repository - git clone https://github.com/shivamkakkar4/pycart.git

### To run Frontend
- cd frontend  
- npm install  
- npm start  
- Server starts on localhost:3000

### To run Server

- Create a virtual environment : virtualenv myenv  
- Activate Virtual environment : myenv\scripts\activate  
- Install Python Requirements : pip install -r requirements.txt
- Run Server : cd backend
             python manage.py runserver
- Server Starts on http://127.0.0.1:8000/
- Create Superuser for Login : python manage.py createsuperuser
- Login to Admin Panel : http://127.0.0.1:8000/admin
