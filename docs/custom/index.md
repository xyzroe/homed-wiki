---
title: 'Custom: Описание'
---

# Custom: Описание

![HOMEd Custom](/assets/img/service/custom.png){width=150px}

_HOMEd Custom_ это сервис для создания виртуальных устройств, а так же для добавления реальных устройств в [структуру](/common/topics/) MQTT-топиков _HOMEd_.

Это может пригодиться, например, для случаев, когда нужно изменять какое-то состояние системы без использования физического выключателя, или чтобы использовать самодельные устройства в автоматизациях _HOMEd_.

## Интеграции

_HOMEd Custom_ поддерживает функцию [Home Assistant MQTT Discovery](https://www.home-assistant.io/integrations/mqtt/#mqtt-discovery). Это значит, что созданные устройства могут быть автоматически "проброшены" в _Home Assistant_, если соответствующий параметр включен в [конфигурации](/custom/configuration/#homeassistant).

Так же устройства могут быть "проброшены" в [Умный дом Яндекса](https://alice.yandex.ru/smart-home) при помощи сервиса [HOMEd Cloud](/cloud/).

## Что дальше?

- [Установка](/custom/installation/)
- [Конфигурация](/custom/configuration/)
- [База данных](/custom/database/)
- [Биндинги](/custom/database/bindings/)

## Полезные ссылки

- [Репозиторий на GitHub](https://github.com/u236/homed-service-custom)
- [Канал проекта в Telegram](https://t.me/homed_info)
