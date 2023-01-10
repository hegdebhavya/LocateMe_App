# LocateMe_App

## About 

Locate me is a simple web application which loactes any place which is entered in the search bar, It also automatically recognizes the country to which that particular place belongs.

<img width="958" alt="image" src="https://user-images.githubusercontent.com/85700971/211665230-e85ab682-5c1a-42bb-9d80-c20c0e5b0eec.png">


## Instruction to run project locally

#### Create a virtual environment
```
python -m venv venv
  ```
#### Activate the virtual environment

* macOS:
```
source venv/bin/activate
```

* Windows:
```
venv\scripts\activate
```

#### Install required dependencies
```
pip install -r requirements.txt
```
#### Run migrations

```
python manage.py makemigrations

python manage.py migrate
```

#### Create an admin user to access the Django Admin interface
```
python manage.py createsuperuser
```

#### Run the application
```
python manage.py runserver
```
