### Модуль фитнес-трекера
Программный модуль фитнес-трекера, который обрабатывает данные для трёх видов тренировок: бега, спортивной ходьбы и плавания. Выполняет следующие функции: принимает от блока датчиков информацию о прошедшей тренировке, определяет вид тренировки, рассчитывает результаты тренировки, выводит информационное сообщение о результатах тренировки (тип тренировки; длительность тренировки; дистанция; среднюю скорость на дистанции; расход энергии, в килокалориях).

### Используемые технологии
- importlib-metadata 4.8.1
- pytest 6.2.5

### Как запустить проект
- Клонировать репозиторий и перейти в него в командной строке:

```git clone https://git@github.com:DmitryOstrovskiy/hw_python_oop.git```

```cd hw_python_oop```

- Cоздать и активировать виртуальное окружение:

```python3 -m venv env```

Windows: ```source venv\scripts\activate```; Linux/Mac: ```sorce venv/bin/activate```

- Установить зависимости из файла requirements.txt:

```python -m pip install --upgrade pip```

```pip install -r requirements.txt```
