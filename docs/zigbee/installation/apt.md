# ZigBee: APT

## Поддерживаемые архитектуры

- `aarch64`
- `arm64`
- `armhf`
- `amd64`

## Добавление GPG-ключа

```sh
sudo wget -O /etc/apt/trusted.gpg.d/debian-homed.asc \
  https://apt.homed.dev/apt.key
```

## Добавление репозитория

```sh
echo "deb https://apt.homed.dev/ debian main" | \
  sudo tee /etc/apt/sources.list.d/homed.list
```

## Установка сервиса

```bash
sudo apt update && sudo apt install homed-zigbee
```

## Что дальше?

После успешной установки _HOMEd ZigBee_ можно переходить к [конфигурации](/zigbee/configuration/).
