# Blogicum

**Blogicum** — это учебный Django-проект, реализующий функциональность блога с постами, страницами и административной панелью.  
Проект создан в рамках спринта 4 курса по Django от Яндекс Практикума.

---
## Установка и запуск
### 1. Клонирование репозитория
```
git clone https://github.com/murale42/blogicum_django_sprint4.git
cd blogicum
```
### 2. Создание и активация виртуального окружения
```
python -m venv venv
venv\Scripts\activate  #source venv/bin/activate в Mac/Linux
```
### 4. Установка зависимостей
```
pip install -r requirements.txt
```
### 5. Применение миграций
```
python manage.py migrate
```
### 6. Создание суперпользователя
```
python manage.py createsuperuser
```
### 7. Запуск сервера
```
python manage.py runserver
```
## Автор
Замуруева Александра