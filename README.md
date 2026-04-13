Create README.md
# QA API Testing Project

## 📌 Описание

Проект посвящён тестированию REST API с использованием Postman.
В рамках проекта были проверены основные CRUD операции и корректность работы сервера.

## 🧪 Что сделано

* Проведено тестирование API (GET, POST, PUT, DELETE)
* Проверены статус-коды и ответы сервера
* Написаны тест-кейсы
* Составлены баг-репорты
* Проверены позитивные и негативные сценарии

## 🛠 Инструменты

* Postman
* Swagger
* JSON

## 📂 Структура проекта

* `test_cases.md` — тест-кейсы
* `bug_reports.md` — баг-репорты
* `postman_collection.json` — коллекция запросов
* `screenshots/` — скриншоты тестирования

## 🎯 Результат

Получен практический опыт тестирования API, работы с документацией и выявления дефектов.

Ниже представлены примеры выполнения API-запросов в Postman:
## 📸 Примеры тестирования

### Получение списка пользователей (200)

![GET users](screenshots/get_users_200.png)

### Получение одного пользователя (200)

![GET user](screenshots/get_user_200.png)

### Создание пользователя (201)

![POST user](screenshots/post_user_201.png)

### Обновление пользователя (200)

![PUT user](screenshots/put_user_200.png)

### Удаление пользователя (204)

![DELETE user](screenshots/delete_user_204.png)

### Негативный тест (баг)

![POST empty body](screenshots/post_user_empty_body_bug.png)

