# Трекер развития

## Миссия продукта
Предоставить начинающим специалистам возможность управления и развития своих приобретенных навыков для успешного поиска работы и целенаправленного профессионального роста.

## Для этого в MVP были реализованы
- Интеграция полученных навыков после прохождения курса.
- Оценка уровня владения конкретным навыком. 
- Индивидуальные рекомендации по повышению уровня владения навыком. 
- Возможность повторной оценки уровня владения навыком.
- Установка индивидуальной цели развития.

### Запуск [backend](https://github.com/hackathon-plus-second-team/development-tracker-backend/tree/develop)

- клонировать репозиторий

```
git@github.com:hackathon-plus-second-team/development-tracker-backend.git
```

- в директории backend/development_tracker создать файл .env и наполнить его по примеру .env_sample

```
DB_ENGINE=django.db.backends.postgresql
POSTGRES_DB=development_tracker
POSTGRES_USER=postgres
POSTGRES_PASSWORD=postgres
DB_HOST=postgres
DB_PORT=5432

DEBUG=True
```
### Предупреждение

```
Если вы используете Windows, убедитесь, что файл run_app.sh имеет формат конца строки LF
```

- перейти в директорию infra

```
cd infra 
```

- запустить сборку контейнеров:

```
docker-compose up -d
```

- проект доступен по адресу:

```
http://localhost/
```
- документация доступна по адресу:

```
http://localhost/api/dynamic_doc/swagger/v1/
```

- после запуска проекта в базе данных уже есть пользователь:

```
{
    "email": "TestUser@yandex.ru",
    "password": "ZQj-hBQ-c83-fmu"
}
```
- также есть superuser:

```
{
    "email": "admin@yandex.ru",
    "password": "admin"
}
```

### Запуск [frontend](https://github.com/hackathon-plus-second-team/development-tracker-frontend)

- клонировать репозиторий

```
git@github.com:hackathon-plus-second-team/development-tracker-backend.git
```

- запустить сборку контейнеров:

```
docker-compose up -d
```
- проект доступен по адресу:

```
http://localhost:5173/
```


## Наша команда

### PRD
[Артем](https://t.me/Aruon19)

### PM
[Наташа](https://t.me/natalya_manannikova)

### SA
[Савелий](https://t.me/savelok)

### Design
[Катя](https://t.me/KatushaEgor)

[Женя](https://t.me/eugi_eugenia)

### Frontend
[Виктор](https://t.me/vitland)

[Даша](https://t.me/delyra_n)

### Backend
[Оля](https://t.me/Olga_Melihova)

[Света](https://t.me/Sunny_in_house)
