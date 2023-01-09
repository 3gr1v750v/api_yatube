# Yatube API

### Описание
Проект позволяет пользователям получать доступ через API к постам, группам, 
подписчикам и комментариям.
Создавать, удалять объекты, редактировать их по своему усмотрению
### Технологии
Python 3.7
Django 2.2.19

### Запуск проекта локально
- Клонировать репозиторий и перейти в него в командной строке
```
git clone https://github.com/EugeniGrivtsov/api_final_yatube.git
cd api_final_yatube
```
- Cоздать и активировать виртуальное окружение:
```
python -m venv env
venv/scripts/activate
```
- Установить зависимости из файла requirements.txt:
```
python -m pip install --upgrade pip
pip install -r requirements.txt
```
Выполнить миграции:
```
python manage.py migrate
```
- Запустить проект:
```
python manage.py runserver
```
## К проекту можно обратиться по адресу 127.0.0.1


### Документация API:
http://127.0.0.1:8000/redoc/

### Разработчик
Eugeni Grivtsov