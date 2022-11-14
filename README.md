# py-taxi-service-deploying

Django project for Taxi service

## Check it out!

[Taxi service deployed to Render](https://taxi-service-oixa.onrender.com/)

## Installation

Python3 must be already installed

#### Download the code
```angular2html
git clone git@github.com:Vlad-Peresta/py-taxi-service-deploying.git
cd py-taxi-service-deploying
```

#### Set Up for Unix, macOS
```angular2html
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

#### Set Up for Windows
```angular2html
python3 -m venv venv
.\env\Scripts\activate
pip3 install -r requirements.txt
```

#### Set Up Database
```angular2html
python3 manage.py makemigrations
python3 manage.py migrate
```

#### Start the app
```angular2html
python manage.py runserver
```

## Features

* Authentication functionality for Driver/User
* Managing drivers, cars and manufacturers directly from website
* Admin panel for advanced management

## Testing website

You can use following superuser for testing website:
* Login: admin.user
* Password: 1qazcde3

## Project screenshots

![image](https://user-images.githubusercontent.com/106173314/201482790-177d78c1-a3e0-4e51-b0b1-acf6acf53ec8.png)
![image](https://user-images.githubusercontent.com/106173314/201482813-23a17087-8779-4c70-bc09-23a96889589d.png)
![image](https://user-images.githubusercontent.com/106173314/201482828-899c568f-af53-49f9-8b9d-9071cd3bc83b.png)
![image](https://user-images.githubusercontent.com/106173314/201482851-8c18d1fc-25a0-4a5b-96c2-4f8d2ef544ef.png)
![image](https://user-images.githubusercontent.com/106173314/201482907-09c9a65c-f4cc-4bc2-b432-a2e8de23f50f.png)
![image](https://user-images.githubusercontent.com/106173314/201482925-1854bee4-8e6c-4658-b836-2c50269118ea.png)
![image](https://user-images.githubusercontent.com/106173314/201482938-36f7efe7-383e-4bc6-af88-aa5126aee591.png)
![image](https://user-images.githubusercontent.com/106173314/201482958-384a253f-787c-4383-877c-1e41f1a750fd.png)
