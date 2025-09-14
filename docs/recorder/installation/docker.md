# Recorder: Docker

## Поддерживаемые платформы

- `linux/arm64`
- `linux/arm/v7`
- `linux/amd64`

## Подготовка

Для запуска [Docker](https://docker.com) контейнера _HOMEd Recorder_ необходимо создать каталог, в котором будут храниться данные и лог сервиса, и поместить в этот каталог файл конфигурации с именем `homed-recorder.conf`. Каталог может иметь произвольное имя, в этой статье используется каталог `/opt/homed-recorder`.

## Пример конфигурации

```ini
[log]
enabled=true

[mqtt]
host=192.168.12.76
port=1883
username=recorder
password=secret
prefix=homed

[database]
file=/data/homed-recorder.db
days=7
debug=false
```

Подробнее о параметрах конфигурации можно почитать [здесь](/recorder/configuration/).

## Запуск контейнера

```sh
docker run \
  --detach \
  --volume /opt/homed-recorder:/data \
  --name homed-recorder \
  docker.u236.org/homed-recorder
```

| Параметр | Описание |
|----------|----------|
| `--volume` | проброс папки `/opt/homed-recorder` на хосте в папку `/data` внутри контейнера |
| `--name`   | название контейнера |
