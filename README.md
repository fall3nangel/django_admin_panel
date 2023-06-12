## `01_docker_compose` - настройка Nginx, Docker и Django.
- Настроен запуск всех компонентов системы (Django, Nginx и Postgresql) с использованием docker-compose.
- Напишите dockerfile для Django.
- версия Nginx убрана из заголовков. 
- Отдача статических файлов Django через Nginx, чтобы не нагружать сервис дополнительными запросами.

## `django_api` — реализация API для выдачи информации о фильме.
Создан API, возвращающий список фильмов в формате, описанном в openapi-файле, и позволяющий получить информацию об одном фильме.
Проверить результат работы API можно при помощи Postman. 
Запустите сервер на 127.0.0.1:8000 и воспользуйтесь тестами из файла movies API.postman_collection.json.

