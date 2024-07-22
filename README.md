# Restaurant Reservation and Menu Management
## Welcome to the Restaurant Reservation and Menu Management System! This project allows users to explore the restaurant menu, make bookings, and learn more about the restaurant.


### FRONTEND VIEW'S
Home:
    URL: /

About Page:
    URL: /about/

Booking Page:
    URL: /book/

Menu Page:
    URL: /menu/

### BACKEND API Endpoints

Menu Items - Retrieve All Menu Items
```
    URL: /api/menu/
    Method: GET
```



Retrieve Specific Menu Item

```
    URL: /api/menu/<int:pk>/
    Method: GET
```



Display Menu Item

```
    URL: /api/menu_item/<int:pk>/
    Method: GET
```



Bookings - Create and List Bookings
```
    URL: /api/bookings/
    Methods: GET, POST
```

Retrieve, Update, and Delete Specific Booking
```
    URL: /api/bookings/<int:pk>/
    Methods: GET, PUT, DELETE
```

## Getting Started
To get a local copy up and running, follow these simple steps.

### Prerequisites
Python 3.x
Django
MySQL


## Installation

### Clone the repo
git clone https://github.com/JMT96/littlelemon-backend-meta.git

### Install Django packages
pip install -r requirements.txt

### Configure your database settings in settings.py.

### Run the migrations

```
python manage.py makemigrations
python manage.py migrate
```


### Start the development server

```
python manage.py runserver
```



## Usage
Visit the homepage at http://127.0.0.1:8000/.

License
Distributed under the MIT License. See LICENSE for more information.

Contact
Your Name - joshunoseke32@gmail.com

Project Link: https://github.com/JMT96/littlelemon-backend-meta