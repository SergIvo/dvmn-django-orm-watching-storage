* Watching Storage Dashboard *

** About **

This is a small Django application made for educational purposes as part of an online course at [dvmn.org](https://dvmn.org/). Application designed to meet requirements listed in [this lesson](https://dvmn.org/modules/django-orm/lesson/watching-storage/) from Django ORM module of mentioned course.

As a simple control point dashboard, application performs the following tasks:

* Querring data about storage visitors by presetted conditions from database using Django ORM;
* Calculates the duration of visitor's presence in the storage;
* Format this information to make it more human-readable and presents it via web interface.

** Running the application **

1. Download application files from GitHub using `git clone` command:
```
git clone https://github.com/SergIvo/dvmn-django-orm-watching-storage
```
2. Use `pip` package manager to install dependencies. Create virtual environment first to avoid conflicts with another versions of same packages:
```
python -m venv venv
```
Then install dependecies from "requirements.txt" in created virtual environment:
```
pip install -r requirements.txt
```
3. Run "main.py" to start the application. Then you should be able to open it in web browser by adress [http://0.0.0.0:8000/](http://0.0.0.0:8000/)
```
python main.py
```


