# Kittygram
### Описание
Учебный проект Kittygram на Docker
Возможности:
- Зарегистрироваться
- Добавить информацию о котике
- Добавить фотографию котика
- Отредактировать или удалить запись

### Запуск

Установить docker
```
sudo apt update
sudo apt install curl
curl -fSL https://get.docker.com -o get-docker.sh 
sudo sh ./get-docker.sh
```
Установить Docker Compose
```
sudo apt-get install docker-compose-plugin 
```
Запуск
```
docker compose up --build
```

### Nginx (пример)
```
server {
    server_name xxx.xxx.xx.xxx;

    location / {
        proxy_pass http://127.0.0.1:9000;
    }

}
```

### Технологии
- Docker
- Docker compose
- Django
- Nginx
- Gunicorn
- PostgreSQL

### Автор
[saturnsergei](https://github.com/saturnsergei)
