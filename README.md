# Web-site

    Сайт разработан на Django==2.2.16. В проекте сделано приложение yatube позволяющее вести новости или блог.
С серверной части реализовано создание постов с добавление изображений, регистрация пользователей, функция изменение пороля.
Написаны собственные тесты для тестирования views, urls, models и forms. Так же были сверстаны основные страницы на html и
добавлен и реализованы некоторые интрумены из bootstrap, такие как навигационная панель.

#Запуск проекта

Клонируем репорзиторий git clone ###

Создаем виртуальное окружение python -m venv venv venv/Scripts/activate

Устанавливаем зависимости pip install -r requirements.txt

Перходим в папку с проектом cd yatube

Запускаем миграции python manage.py makemigrations python manage.py migrate

Запускаем проект python manage.py runserver
