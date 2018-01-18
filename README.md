# Шаблон веб-сервиса на API Platform

# Установка для окружения разработчика

```
git clone https://github.com/bskton/api-platform-server.git
cd api-platform-server
sudo docker-compose up -d
sudo docker-compose exec app bin/console doctrine:schema:create
```

Открыть в браузере http://localhost