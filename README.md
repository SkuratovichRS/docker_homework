## Инструкция по запуску
1. Билд образа: `docker build -t custom_nginx:latest .`
2. Запуск контейнера: `docker run -p 80:80 -d custom_nginx:latest`
3. Проверка работы: http://localhost
