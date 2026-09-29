# API Testing - Wishlist Project

## Обзор
Автоматизированное тестирование REST API приложения Wishlist с использованием Postman.

**Base URL:** `https://api.wishlist.otus.kartushin.su`

**API Documentation:** [Swagger UI](https://api.wishlist.otus.kartushin.su/swagger-ui/index.html)

## Тест-план

### Покрытие API
Протестировано **16 эндпоинтов** в 4 категориях:

1. **Authentication** (2 эндпоинта)
    - Регистрация пользователя
    - Авторизация (получение токена)

2. **Wishlists** (6 эндпоинтов)
    - Создание подарка
    - Получение списка по ID
    
3. **Gifts** (6 эндпоинтов)
    - Получение подарка по id
    - Резервирование подарка
    - Обновление подарка
    - Удаление подарка
    - Удаление списка

4. **Users** (2 эндпоинта)
    - Получение всех пользователей
    - Получение списков пользователя по ID

### Всего тестов: 22
- ✅ Позитивные тесты: 16
- ✅ Негативные тесты: 4

## Инструкция по запуску

### Импорт в Postman:
1. Откройте Postman
2. **File → Import**
3. Выберите файл `Postman/Wishlist API Collection.postman_collection.json`
4. Импортируйте окружение `Postman/Wishlist API Environment.postman_environment.json`
5. Активируйте окружение
6. Запустите **Collection Runner**

## Структура коллекции
