# API для проекта Yatube :t-rex:

Данный проект является учебной частью созданной командой "Яндекс-Практикум"

В API YATUBE можно получить или создать запись, комментарий, группу.


```Возможности:```

- Подписка на пользователей

- Просмотр, создание, удаление и модификация постов

- Просмотр и создание групп

- Просмотр, создание, удаление и модификация комментариев

- Фильтрация по полям

## Установка

 ```Для работы необходим Python версии 3.9 .```

В директории с скачанным проектом нужно создать и заупстить виртуальное окружение:

```Установка/активация виртуального окружения```

- python3 -m venv env

- source venv/bin/activate

```Установка зависимостей```

- python3 -m pip install --upgrade pip

- pip install -r requirements.txt

```Выполнить миграции```

- python3 manage.py migrate

```Запуск```

- python manage.py runserver

### Примеры доступных запросов

```пример POST-запросов:```

http://127.0.0.1:8000/api/v1/users/

http://127.0.0.1:8000/api/v1/posts/

http://127.0.0.1:8000/api/v1/posts/1/

### После запуска сервера вам будет доступна документация
>http://127.0.0.1:8000/redoc

```Проект написан:```Сидоровым Виктором

```Ревью проекта:```Никита Левашов

Stack:

```Python 3.9```

```Django REST Framework (DRF)```

```REST API```

```Djoser```
