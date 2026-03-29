# 📃 Laravel boilerplate

## Используя данный репозиторий вы получаете:

1. **Сборку Docker-контейнеров**:
    - `php:8.5-fpm`
    - `nginx:alpine`
    - `postgres:15-alpine`
    - `redis:8-alpine`
    - `rabbitmq:3-management-alpine`

2. **Некоторые элементы, которые могут ускорить разработку:**
    - `App\Traits\ResponseTrait` — обёртка над `JsonResponse` для упрощения возврата API-ответов
    - `Exceptions`:
        - `InternalServerErrorException`
    - `Makefile` - позволяет легко взаимодействовать с Docker, без написания полных комманд

