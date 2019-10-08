# Weatherapp
## Run application for development using docker-compose
- Get openweathermap api key
- Put it in .env (please use .env.example as an example)
- run docker-compose
```
docker-compose up -d
```
or
```
docker-compose up --build
```
(if rebuild required)

## Check if hot reload enabled

- edit backend/src/index.js (TARGET_CITY, for example)
- edit frontend/src/public/index.html 
- make sure that changes applied without any restarts

## Deploy to  "production"

- trigger pipeline here https://gitlab.com/efitasks/testweatherapp

