---
title: 'Cloud: Docker'
---

# Cloud: Docker

## Поддерживаемые платформы

- `linux/arm64`
- `linux/arm/v7`
- `linux/amd64`

## Подготовка

Для запуска [Docker](https://docker.com) контейнера _HOMEd Cloud_ необходимо создать каталог, в котором будут храниться данные и лог сервиса, и поместить в этот каталог файл конфигурации с именем `homed-cloud.conf`. Каталог может иметь произвольное имя, в этой статье используется каталог `/opt/homed-cloud`.

## Пример конфигурации

```ini
[log]
enabled=true

[mqtt]
host=192.168.12.76
port=1883
username=cloud
password=secret
prefix=homed

[cloud]
host=cloud.homed.dev
port=8042
uniqueid=docker_client_1
token=zyxwvutsrqponmlkjihgfedcba9876543210
```

Подробнее о параметрах конфигурации можно почитать [здесь](/cloud/configuration/).

## Запуск контейнера

```sh
docker run \
  --detach \
  --volume /opt/homed-cloud:/data \
  --name homed-cloud \
  docker.u236.org/homed-cloud
```

| Параметр | Описание |
|----------|----------|
| `--volume` | проброс папки `/opt/homed-cloud` на хосте в папку `/data` внутри контейнера |
| `--name`   | название контейнера |
