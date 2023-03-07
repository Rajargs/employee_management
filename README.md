# employee_management

#install necessary packages by running below command

pip3 install -r requirements.txt

#Do db changes in the settings.py file in DATABASES variable for the db config

#Prepare database migration by running below command

python3 management/manage.py makemigrations

#Create required tables in database for the project by below command

python3 management/manage.py migrate

#create admin user by below command

python3 management/manage.py createsuperuser

#Finally run the project

python3 management/manage.py runserver

#In the url go to http://127.0.0.1:8000/show