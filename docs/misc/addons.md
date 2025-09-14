# Home Assistant Add-ons

Некоторые сервисы _HOMEd_ можно использовать как [дополнения](https://www.home-assistant.io/addons) для операционной системы [Home Assistant OS](https://www.home-assistant.io/installation/). На данный момент дополнения доступны для следующих сервисов:

- [HOMEd ZigBee](/zigbee/)
- [HOMEd Custom](/custom/)
- [HOMEd Automation](/automation/)
- [HOMEd Recorder](/recorder/)
- [HOMEd Web](/web/)
- [HOMEd Cloud](/cloud/)

## Репозиторий

Адрес репозитория с дополнениями _HOMEd_:
```
https://github.com/u236/homed-ha-addons
```

## Конфигурация

Файлы конфигурации сервисов хранятся на хосте, в папках `/addon_configs/<addon slug> `. Для редактирования файлов конфигурации можно использовать дополнение [File Editor](https://github.com/home-assistant/addons/blob/master/configurator/README.md) c ___выключенной___ опцией "Enforce Basepath".
