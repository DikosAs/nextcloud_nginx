# Nextcloud from docker-compose
#### Author: [Marsh Meg](https://github.com/DikosAs)
# How to use:
### Install Docker ([guide](https://docs.docker.com/engine/install/ubuntu/))
### Clone repository
    git clone https://github.com/DikosAs/nextcloud_nginx.git
    cd nextcloud_nginx
### Create and change `.env` file
    vim .env
```
# config exemple
DB_ROOT_PASSWORD=   # passwort for root user 
DB_USER=            # user for cloud 
DB_PASSWORD=        # password for user 
DB_DATABASE=        # db name
DOMAINS=            # trusted domains
CLOUD_DATA_DIR=     # datadir in cloud conteinser
```
### Run app
    docker compose up -d
### Go to http://localhost

---
### Установить Docker ([инструкция](https://docs.docker.com/engine/install/ubuntu/))
### Клонировать репозиторий
    git clone https://github.com/DikosAs/nextcloud_nginx.git
    cd nextcloud_nginx
### Создать и настороить `.env` файл:
    vim .env
```
# config exemple
DB_ROOT_PASSWORD=   # passwort for root user 
DB_USER=            # user for cloud 
DB_PASSWORD=        # password for user 
DB_DATABASE=        # db name
DOMAINS=            # trusted domains
CLOUD_DATA_DIR=     # datadir in cloud conteinser
```
### Запустить приложение
    docker compose up -d
### Перейти http://localhost

---
## Links
* https://nextcloud.com/
* https://github.com/nextcloud
* https://hub.docker.com/_/nextcloud/