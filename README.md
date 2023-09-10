# Kittygram — социальная сеть для обмена фотографиями любимых питомцев.


## Это полностью рабочий проект, который состоит из бэкенд-приложения на Django и фронтенд-приложения на React.
## Что умеет проект:

- Добавлять, просматривать, редактировать и удалять котиков.
- Добавлять новые и присваивать уже существующие достижения.
- Просматривать чужих котов и их достижения.

## Установка:
1. Клонируйте репозиторий на свой компьютер:
```git clone git@github.com:mdflamingo/kittygram_final.git```
```cd kittygram```
2. Создайте файл .env и заполните его своими данными. Перечень данных указан в корневой директории проекта в файле .env.

## Создание Docker-образов
1. Замените username на ваш логин на Dockerhub:
```
cd frontend
  docker build -t username/kittygram_frontend .
  cd ../backend
  docker build -t username/kittygram_backend .
  cd ../nginx
  docker build -t username/kittygram_gateway . 

```
2. Загрузите образы на DockerHub:
```
  docker push username/kittygram_frontend
  docker push username/kittygram_backend
  docker push username/kittygram_gateway
```

## Автор
Анастасия Вольнова
