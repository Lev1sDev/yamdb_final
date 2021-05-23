# API Yamdb
![yamdb_workflow](https://github.com/Lev1sDev/yamdb_final/actions/workflows/yamdb_workflow.yaml/badge.svg)

## База отзывов пользователей о фильмах, музыке и книгах
## Стек технологий: Python 3, Django REST Framework, PostgreSQL, Simple-JWT, NGINX, Docker, GitHub Actions, Яндекс.Облако (Ubuntu 18.04)

### Запуск приложения:
``` git clone https://github.com/Lev1sDev/infra_sp2.git  ``` \
```docker-compose up```

### Выполнить миграции:
```docker-compose exec web python manage.py makemigrations api``` \
```docker-compose exec web python manage.py migrate --noinput```

### Создать суперпользователя:
```docker-compose exec web python manage.py createsuperuser```

### Привязать статические файлы:
```docker-compose exec web python manage.py collectstatic --no-input```

### Заполнить базу начальными данными:
```docker-compose exec web python manage.py loaddata --exclude=auth --exclude=contenttypes fixtures.json```

## Адрес сайта: http://130.193.52.141/api/v1/

## Мои контакты
### Telegram: @azikovlev
### Почта: azikovlev@yandex.ru
### Резюме: https://spb.hh.ru/resume/682d8c77ff08ea8cb80039ed1f4670366e6b73
