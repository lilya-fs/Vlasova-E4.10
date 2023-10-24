# skillfactory-E4.10

# Задача
Как системному администратору данной организации вам поставлена задача собрать на докер образ Django (Linux, nginx, Django, Postgres, Gunicorn) сервера,
который можно было бы выложить в публичный доступ на Docker Hub, предоставляя кандидату только ссылку на образ и команду для установки.
Все нужные сервисы должны быть проброшены на хост по стандартным портам, реализация HTTPS не требуется, версии Django, nginx и Postgres не имеют значения,
как и версия ядра Linux. В проекте просто должна работать админка с заранее прописанным логином и паролем.

# Запуск
- Склонировать репозиторий git clone https://github.com/EastSmog/skillfactory-E4.10.git
- Перейти в директорию репозитория из текущей cd skillfactory-E4.10
- Установка и запуск docker-compose up -d
- Админка: http://localhost:8000/admin/
- login: adm
- password: admin
