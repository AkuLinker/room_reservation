# room_reservation

### Описание
api для резервирования переговорных комнат.

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone 
```

```
cd room_reservation
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

```
source venv/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Применить миграции:

```
alembic upgrade head
```

Запустить проект:

```
uvicorn app.main:app --reload
```
