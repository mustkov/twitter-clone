# Twitter-clone

![twitter](https://user-images.githubusercontent.com/49994180/169691266-cf664ec8-c433-47e1-8cf5-4d85119d9b4e.png)

## Установка

1. Установите Docker Desktop
2. Находясь в корневой папке проекта

```shell
cd backend-nest
npm install

cd ..

cd frontend
npm install --force
```

3. Docker

```shell
# Находясь в корневой папке проекта
cd docker
docker compose up
```

4. Запуск backend

```shell
cd backend-nest
npm run start:dev
```

5. Запуск frontend

```shell
cd frontend
npm run start
```

## REST API Testing

Используйте эти примеры маршрутов для тестирования в Postman или любом другом инструменте REST API, который вы используете:

### GET all tweets

Request: GET
Route: [http://localhost:8080/tweets](http://localhost:8080/tweets)

### GET tweet by ID

Request: GET
Route: [http://localhost:8080/tweets/ID](http://localhost:8080/tweets/ID)

### CREATE tweet

Request: POST
Route: [http://localhost:8080/tweets](http://localhost:8080/tweets)

Body raw: {"tweet": "Hello World", "img": ""}

### UPDATE tweet by ID

Request: POST
Route: [http://localhost:8080/tweets/ID](http://localhost:8080/tweets/ID)

Body raw: {"tweet": "Hello Moon", "img": ""}

### DELETE tweet by ID

Request: DELETE
Route: [http://localhost:8080/tweets/ID](http://localhost:8080/tweets/ID)
