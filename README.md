# API Yatube project
### Описание
Проект «API для Yatube». Данный проект является API социальной сети Yatube.
### Технологии
Python, DRF, JWT + Djoser
### Как запустить проект:
- Клонировать репозиторий и перейти в него в командной строке:
```
git clone https://github.com/AlexandrPthn/api_final_yatube.git
cd api_final_yatube
``` 
- Cоздать и активировать виртуальное окружение:
```
python3 -m venv env
source env/bin/activate
``` 
- Установить зависимости из файла requirements.txt:
```
python3 -m pip install --upgrade pip
pip install -r requirements.txt
``` 
- Выполнить миграции:
```
python3 manage.py migrate
``` 
- Запустить проект:
```
python3 manage.py runserver
``` 
### Авторы
Кокушин Александр