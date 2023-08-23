# API для YaTube

### Описание:
API для социальной сети, который позволяет пользователям, публиковать записи, комментировать записи, подписываться на авторов.

### Технологии:
+ Python
+ Django 
+ DRF
+ JWT + djoser

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:AlexanderMorozovIL/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

* Если у вас Linux/macOS

    ```
    source venv/bin/activate
    ```

* Если у вас windows

    ```
    source venv/scripts/activate
    ```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

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

Автор - [Морозов Александр](https://github.com/AlexanderMorozovIL)
