# API для Yatube
## Описание:

Можно публиковать посты, редактировать, подписываться на авторов, комментировать посты

### Технологии: 

Python3,

Django,

Django REST Framework

Как запустить проект:

- Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/mrSHISKA/api_final_yatube.git
```

```
cd api_final_yatube
```

- Cоздать и активировать виртуальное окружение:

```
python -m venv venv
```

```
source venv/bin/activate
```

- Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

- Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```