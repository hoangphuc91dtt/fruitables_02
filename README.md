## Cài môi trường

```bash
pip install virtualenv
```

## Tạo môi trường

```bash
virtualenv env
```

```bash
env\Scripts\activate
```

## Tải package

```bash
pip install -r requirements.txt
```

## run server

```bash
pip install -r requirements.txt
```

## run db

```bash
python manage.py makemigrations upload
python manage.py makemigrations products
python manage.py makemigrations user
python manage.py makemigrations orders
python manage.py migrate
python manage.py makemigrations
python manage.py runserver
```

# Nếu có **Lỗi** thì:

- Có lỗi thì mình làm như này nha thầy:
- xóa folder migrations (nếu có)
- xóa file db.sqlite3
