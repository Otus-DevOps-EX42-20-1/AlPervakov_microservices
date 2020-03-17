# AlPervakov_microservices
AlPervakov microservices repository

# Dosker
Создан Dockerfile
Создан свой образ и залит на Docker Hub
Работа с dosker-machine

Собраны образы для сервисного приложения
Оптимизирован образ с UI
Создана сеть в докере
Создан Docker volume для БД

По умолчанию, все контэйнеры, которые запускаются с помощью docker-compose, используют название текущей директории как префикс. Префикс используется, когда мы хотим сослаться на контейнер из основного docker-compose файла. Чтобы зафиксировать префикс, нужно создать файл .env рядом с конфигурационными файлами docker-compose в той директории, из которой запускается docker-compose.
`COMPOSE_PROJECT_NAME=<ПРЕФИКС>`

# Мониторинг
Ссылка на DockerHub `https://hub.docker.com/u/apervakov`

# Логирование
Сбор неструктурированных логов
Визуализация логов
Сбор структурированных логов
Распределенная трасировка

# Kubernetes
Пройден Kubernetes THW
Развернуто и запущено приложение Reddit в GKE
Результат: https://ibb.co/Fs49sRt
