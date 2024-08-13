# Django course app

This is a Django application designed to be deployed on cloud platforms. It showcases the integration of a Django web application with cloud services.

## Features

- User authentication and authorization
- Basic CRUD operations
- Integration with cloud databases
- Deployment on cloud platforms like IBM Cloud, AWS, or Google Cloud
- Responsive web design

## Installation

To get started with the project, follow these steps:

### 1. Clone the Repository

``` 
git clone https://github.com/zoubidabenlem/Django_cloud_app.git
cd Django_cloud_app
```
### 2. Create and Activate a Virtual Environment
> On Windows (PowerShell)
```
python -m venv djangoenv
.\djangoenv\Scripts\Activate
```
>On macOS/Linux
```
python3 -m venv djangoenv
source djangoenv/bin/activate
```
### 3. Install Dependencies
```
pip install -r requirements.txt
```
### 4. Apply Migrations
```
python manage.py migrate
```
5. Run the Development Server
```
python manage.py runserver
```