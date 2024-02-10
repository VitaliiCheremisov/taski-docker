# Учебный проект taski-docker

Проект taski-docker, работает в контейнерах Docker и имеет CI/CD GitHubActions
Задача проекта:
- Написание образов Docker для предоставленного проекта
- Упаковка backend-Django, frontend-React, getaway-Nginx в контейнеры Docker Compose
- Настройка CI/CD с помощью  GitHubActions

## Что нужно сдлеать

Склонировать репозиторий на ваш локальный компьютер
```
git clone https://github.com/VitaliiCheremisov/taski-docker.git
```
Запустить проект локально
```
docker-compose up
```
Запустить проект можно на удаленном серверe Docker
```
sudo docker-compose up -d
```
Технологии
```
Python 3.10
Django 3.2.3
Django REST framework 3.14
Nginx
Docker
```
Автор
- [Виталий Черемисов](https://github.com/VitaliiCheremisov)