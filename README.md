# Postman API Tests for ReqRes

Коллекция автотестов для тестового API [Reqres.in](https://reqres.in).

## 📋 Что тестируется

| Метод | Эндпоинт | Описание |
|-------|----------|----------|
| POST | `/api/login` | Авторизация, получение токена |
| GET | `/api/users/2` | Получение пользователя по ID |
| POST | `/api/users` | Создание нового пользователя |
| PUT | `/api/users/2` | Обновление пользователя |
| DELETE | `/api/users/2` | Удаление пользователя |
| GET | `/api/users?page=2` | Получение списка с пагинацией |

## 🛠️ Как использовать

1. Скачай и импортируй в Postman:
   - Коллекцию (`Regres_API_Test.json`)
   - Окружение (`ReqRes_API_Environment.json`)

2. Добавь переменную `x-api-key` в окружении (получи ключ на [app.reqres.in](https://app.reqres.in))

3. Выбери окружение **"ReqRes API"** в Postman

4. Запускай запросы в порядке:
   - `POST Get and save user token`
   - `GET Get user by id`
   - `POST Create new user`
   - `PUT Update user`
   - `DELETE Delete user`
   - `GET Get users list`

## 📸 Результаты тестов

Все тесты проходят успешно:

![Test Results](screenshots/test-results.png)

## 👤 Автор

Сотиков Игорь
