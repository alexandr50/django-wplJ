1. Склонируйте репозиторий себе на локально git clone https://github.com/alexandr50/TestNova.git
2. Перейдите в папку app и устновите зависимости из requirements.txt
3. Создайте сервисный аккунт в google api drive
4. Сгенерируйте ключ в формате json и положите этот файл по пути file/data_files в файл data_json'
5. Запустите сервер джанго python manage.py runserver
6. По урлу http://127.0.0.1:8000/files/create введите данные для создания файла в google api drive

7. Так же приложение доступно по адрессу django-server-anlq-production.up.railway.app/files/create




# Тестовое задание веб-программист (Python)

Сделать API метод, который можно будет запустить POST запросом с параметрами:

1. data = Текстовое содержимое файла
2. name = Название файла

Необходимо создать в google drive документ с названием = name и содержимым = data

Предварительно нужно создать Гугл аккаунт пустой и авторизовать приложение, чтобы получить токены

<aside>
💡 Ориентировочное время решения - до 2ч. Решение нужно прислать в течение недели после получения.

</aside>

**Нужно использовать:**

- Фреймворк Django

**Критерии оценки:**

- Работоспособность согласно ТЗ
- Архитектура решения
- Удобство чтения кода и комментарии
- Удобство проверки(GIT + развернутый рабочий сервер на момент проверки)

Сервер достаточно держать в течение 2х дней после отправки решения, чтобы мы могли провести тесты

Результат тестового задания необходимо отправить в HH:

1. Ссылка на [репозиторий](https://github.com/)
2. URL и описание метода
