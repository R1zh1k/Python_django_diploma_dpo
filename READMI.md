# Интернет магазин техники MEGANO


</h3>
Представляет собой подключаемое django-приложение. Берет на себя все что связано с отображением страниц, а обращение
за данными происходит по API, который реализован с использованием Django Rest Framework.


## Установка и запуск проекта
1. Скачать репозиторий.
2. Установить виртуальную среду python -m venv <название>.
2. Установить зависимости `pip install -r requirements.txt` 
3. Установка frontend:
    * `cd diploma-frontend && python setup.py sdist` - создание архива с библиотекой фронтенда
    * `pip install ./dist/diploma-frontend-0.6.tar.gz` - установка фронтенда
4. Создать и применить миграции:
    * `python manage.py make migrations`
    * `python manage.py migrate`
5. Запуск сервера
   * `python manage.py runserver`

