# Currency Parser

Простое Spring Boot приложение для получения курсов валют и сохранения их в базу H2.

## Доступ

http://localhost:8080/answer

## Примеры запросов

- `GET /answer?currency=USD` — курс доллара  
- `GET /answer?date=2025-12-29` — курсы за указанную дату  
- `GET /answer?currency=EUR&date=2025-12-29` — фильтр по валюте и дате

## Запуск

```bash
mvn spring-boot:run
