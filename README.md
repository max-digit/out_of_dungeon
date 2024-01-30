# Мини-игра **"Подземелье. Путь наверх"**

Мини-игра из [курса по фреймворку Flask (на stepik.org)](https://stepik.org/lesson/536750/step/2?unit=529973)
Цель игры в том, чтобы выбраться из подземелья на поверхность.

Для работы приложения нужно установить зависимости из файла requirements.txt:

- ```pip install -r requirements.txt```

Для старта приложения запустите файл app.py:

- через Python в командной строке/терминале: ```python app.py```
- через Flask: ```flask run```

Затем в браузере введите адрес localhost:5000 или 127.0.0.1:5000, и - добро пожаловать!

Управление производится введением данных в поля формы на странице, либо в адресную строку. Если вы желаете вводить данные в адресную строку, то в ней нужно набрать адрес в следующем формате (после "localhost:5000/game/<Ваше имя>/"):

- <направление>/<количество шагов>, где

    направление - это однa из сторон света: "север", "восток", "юг", "запад",

    количество шагов - любое целое число.
