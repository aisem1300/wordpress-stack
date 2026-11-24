# WordPress + MySQL + phpMyAdmin (Docker)

## Запуск
1. `cp .env.example .env` і змініть паролі
2. `docker compose up -d`
3. WordPress: http://localhost:8080
4. phpMyAdmin: http://localhost:8081

## Зупинка
`docker compose down` (дані збережуться), `docker compose down -v` (видалити разом із даними)
