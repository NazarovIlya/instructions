## MVP на WordPress

### Настройка окружения и разворачивание docker-контейнера

- [Установить Docker Desktop на ПК](https://www.docker.com/products/docker-desktop/)

- Запустить програму Docker Desktop

- [При необходимости обновить WSL (Подсистема Windows для Linux) до WSL2](https://learn.microsoft.com/ru-ru/windows/wsl/install-manual)

- В PowerShell  выполнить команду docker-compose up -d --build

- И поднять docker-compose с помощью команды docker-compose up -d

- Инсталлятор WordPress находится по адресу localhost:8081

- К админке myPhpAdmin можно обратиться по адресу localhost:8080

- При необходимости порты можно поменять (первый в XXXX:XXXX) на свободные, изменив docker-compose.yml в 25 и 42 строках

- Снова выполнить docker-compose up -d --build и docker-compose up -d

- И обращаться уже по localhost:XXXX

- Сам docker-compose.yml можно [взять отюда](resource/docker-compose.yml)

[Немного о Docker](https://t.me/iksergeyru/40)

[Побольше слов о контейнеризации](https://www.youtube.com/playlist?list=PLU2ftbIeotGoGFC_2lj-OplT_cItXfu48)
