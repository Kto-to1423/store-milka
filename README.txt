Создаём виртуальное окружение
python -m venv venv 

активируем виртуальное окружение
venv\scripts\activate 

обновляем пакетный менеджер
python -m pip install --upgrade pip 

устанавливаем фреймворк
pip install django 

Создаём проект
django-admin startproject store_project

переходим в папку store_project
cd store_project 

создаём приложение 
python manage.py startapp store

подключаем базу данных
python manage.py migrate

запускаем сервера
python manage.py runserver

при изменении структуры базы данных
python manage.py makemigrations
python manage.py migrate

регистрируем администратора
python manage.py createsuperuser

работа с изображениями
pip install pillow