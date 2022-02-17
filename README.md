### Описание итогового проекта
    Краткое описание сервиса:
    1 - Django_shop - Приложение магазина
    2 - Flask - Приложение Админка для магазина
    3 - Rabbitmq - очередь сообщений
    4 - Приложение "ремонта телефонов"


Реализация польностью на микросервисной архитектуре (docker).

### Установка и развертывание:
#### Установим docer для своей операционной системы:
    # windows 10
    https://docs.docker.com/desktop/windows/install/

    # debian
    https://docs.docker.com/engine/install/debian/

#### После установки docker нужно склонировать репозиторий 
    git clone git@github.com:romiras-coder/Django_Flask_Rabbit.git
    
#### После запускаем сборку сервиса
    docker-compose build 