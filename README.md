# 💻 Laravel boilerplate

## Используя данный репозиторий вы получаете -:

1. **Сборку Docker-контейнеров**:
    - `php:8.4-fpm-alpine`
    - `nginx:alpine`
    - `postgres:15-alpine`
    - `pgadmin4`
    - `redis:8-alpine`
    - `rabbitmq:3-management-alpine`

2. **Встроенные классы для упрощения написания кода:**
    - `Enum`: `HttpStatus` — содержит HTTP статус-коды
    - `Trait`: `ResponseTrait` — обёртка над `response()->json()` для упрощения возврата API-ответов
    - `Exceptions`:
        - `InternalServerErrorException`
        - `InvalidCredentialsException`

