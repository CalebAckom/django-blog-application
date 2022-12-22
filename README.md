# Blog Application
My first Django application

#  Setting Up

1. Clone the project
```
git clone https://github.com/CalebAckom/django-blog-application.git
```
2. Change the directory
```
cd blog-application
```
3. Create .env file. Reference .env.example to see the needed variables
```
touch .env
```
4. Install packages
```
pip install -r requirements.txt
```
5. Create inital database schema
```
python3 manage.py makemigrations
```
```
python3 manage.py migrate
```
6. Start the application
```
python3 manage.py runserver
```