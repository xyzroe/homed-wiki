# Automation: Docker

## Поддерживаемые платформы

- `linux/arm64`
- `linux/arm/v7`
- `linux/amd64`

## Подготовка

Для запуска [Docker](https://docker.com) контейнера _HOMEd Automation_ необходимо создать каталог, в котором будут храниться данные и лог сервиса, и поместить в этот каталог файл конфигурации с именем `homed-automation.conf`. Каталог может иметь произвольное имя, в этой статье используется каталог `/opt/homed-automation`.

## Пример конфигурации

```ini
[log]
enabled=true

[mqtt]
host=192.168.12.76
port=1883
username=automation
password=secret
prefix=homed

[automation]
database=/data/database.json

[location]
latitude=55.755864
longitude=37.617698

[telegram]
token=1234567890:abcdefghijklmnopqrstuvwxyz123456789
chat=123456789
timeout=60
```

Подробнее о параметрах конфигурации можно почитать [здесь](/automation/configuration/).

## Запуск контейнера

```sh
docker run \
  --detach \
  --volume /opt/homed-automation:/data \
  --name homed-automation \
  docker.u236.org/homed-automation
```

| Параметр | Описание |
|----------|----------|
| `--volume` | проброс папки `/opt/homed-automation` на хосте в папку `/data` внутри контейнера |
| `--name`   | название контейнера |

## Что дальше?

После настройки _HOMEd Automation_ можно приступать к добавлению автоматизаций в [базу данных](/automation/database/).
