# Taxi Service

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
![image](https://user-images.githubusercontent.com/106173314/202036075-0d52b645-55ff-41a7-9e40-c688a5aba03b.png)
![image](https://user-images.githubusercontent.com/106173314/202036183-d104b440-a330-4760-96c5-723fd5709422.png)
![image](https://user-images.githubusercontent.com/106173314/202036415-0e622e7a-ad3d-48fa-8296-957209d7f43d.png)
![image](https://user-images.githubusercontent.com/106173314/202036460-6419e548-33ee-4022-8ab4-29afa4ed8b5e.png)
