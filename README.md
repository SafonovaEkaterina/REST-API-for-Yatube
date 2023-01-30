# REST API для проекта "Yatube"

### Описание
REST API для проекта Yatube реализует взимодействие с базой данных, а именно:
- создание, 
- получение, 
- редактирование, 
- удаление постов и комментариев, 
- получение списка сообществ и информации об отдельном сообществе, 
- подписки на пользователей. 
Используется аутентификация по JWT-токену.

### Технологии
- Python 3.7.9
- Django 3.2.16 
- Django REST Framework 3.12.4
- Djoser  

### Запуск проекта в dev-режиме

- Cоздать и активировать виртуальное окружение
```
python -m venv env
source venv/Scripts/activate
python -m pip install --upgrade pip
```

- Установить зависимости из файла requirements.txt
```
pip install -r requirements.txt
```

- Выполнить миграции
```
python manage.py migrate
```

- Запустить проект
```
python manage.py runserver
```
### Документация
Документация доступна по адресу [http://127.0.0.1:8000/redoc](http://127.0.0.1:8000/redoc).
