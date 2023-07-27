# Kittigram


## О проекте

Социальная сеть для любителей кошачих.
Здесь вы можете загружать фотографии котов и кошек, добавить их достижения (проделки), а также просматривать котиков других пользователей

## Стек технологий

- Python
- Django
- djangorestframework
- Nginx
- gunicorn

## Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:
```
git clone https://github.com/<Ваше Имя>/api_final_yatube.git
```

Cоздать и активировать виртуальное окружение:

```
python -m venv venv
```

```
source venv/Script/activate
```

Установить зависимости из файла requirements.txt:

```
python -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```

P.S. В директории infra_sprint1 необходимо создать файл .env и прописать SECRET_KEY:
```
SECRET_KEY = '<Ваш Ключ>'
```

## Автор:
 :grinning: Lenar :sunglasses:
