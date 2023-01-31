# stepic_game_of_life
## Проект stepik. Игра "Жизнь"
### Описание:
Клеточный автомат, придуманный английским математиком Джоном Конвеем в 1970 году. Это игра без игроков, в которой человек создаёт начальное состояние, а потом лишь наблюдает за её развитием.
На текущий момент у меня нет знаний по части API или POST/GET запроссов на уровне, чтобы реализовать этот проект более презентабельно. Поэтому для шага 3.3 на курсе "Web-фреймворк Flask: введение" (https://stepik.org/course/97540/promo) хватит.

### Технологии:
![Flask](https://img.shields.io/badge/Flask-2.2.1-green)
![Jinja2](https://img.shields.io/badge/Jinja2-3.1.1-green)

### Инструкция по запуску:
Клонировать репозиторий и перейти в него в командной строке:
```
git clone https://github.com/LunarBirdMYT/stepic_game_of_life.git
```

```
cd stepic_game_of_life
```

Cоздать и активировать виртуальное окружение:

```
python -m venv env
```

```
source env/bin/activate
```

```
python -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

### Как запустить проект:
Необходимо сообщить фласку, какой файл требуется запускать. Для этого используется команда:
```
set FLASK_APP=app.py  Для Windows
```
ИЛИ
```
export FLASK_APP=app.py  Для Unix-систем
```
После чего запустить проект:
```
flask run
```
и перейти на стандартный адрес http://127.0.0.1:5000/ в браузере.

