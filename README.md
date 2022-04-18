# API для YaTube
### Описание проекта
Позволяет делиться мыслями и записями в постах с другими пользователями социальной сети.
Присутствует возможность комментирования записей, подписки на интересующих авторов.
### Технологии
Python 3.7
Django 2.2.19
### Запуск в dev-режиме
Клонировать репозиторий и перейти в него в командной строке:
```
git clone git@github.com:JediMode/api_final_yatube.git
```
```
cd api_final_yatube/
```
Установить виртуальное окружение, затем активировать его:
```
python3 -m venv env
```
```
source env/bin/activate
```
Установить зависимости из файла requirements.txt:
```
python3 -m pip install --upgrade pip
```
```
pip install -r requirements.txt
```
Выполнить миграции:
```
python3 manage.py migrate
```
Запустить проект:
```
python3 manage.py runserver
```