# Документация REST API (Лабораторная работа №2)
**Студент:** Тачгулиев
### 1. GET /api/text
Ответ (200 OK): Привет, это текстовый ответ от Tachguliev!
### 2. GET /api/info
Ответ (200 OK): {"student": "Tachguliev", "status": "online"}
### 3. GET /api/items
Успешный запрос (?id=1): 200 OK -> {"id": 1, "name": "Ноутбук", "owner": "Tachguliev"}
Ошибка (?id=999): 404 Not Found -> {"error": "Товар не найден (404 Not Found)"}
