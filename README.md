# my-first-image

Мой первый Docker-проект: сайт на nginx и база данных Redis, которые запускаются вместе через docker-compose.

## Как запустить

1. Установить Docker
2. Скачать проект: git clone https://github.com/ZEHAHAHAHA1/my-first-image.git
3. Зайти в папку проекта и запустить: docker compose up -d
4. Открыть в браузере: http://localhost:8080

## Что внутри

- Dockerfile: образ на основе nginx:alpine с моей страницей
- docker-compose.yml: два сервиса, website и database (Redis)
- index.html: страница сайта
