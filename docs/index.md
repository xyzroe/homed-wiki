# HOMEd

_HOMEd_ это набор легковесных сервисов для организации системы умного дома, среди которых есть сервисы для работы с ZigBee-сетью, веб-интерфейс, рекордер статистики, служба автоматизаций и многое другое, включая возможность интеграции с [Home Assistant](https://www.home-assistant.io) и [Умным домом Яндекса](https://alice.yandex.ru/smart-home).

Сама идея заняться всем этим, как и большинство хороших идей, возникла по причине банальной лени - в один преркрасный день я просто не захотел вставать с кровати, чтобы перед сном выключить во всем доме свет, _и тут началось_. Это история проб и ошибок длиной в несколько лет, прошедшая все этапы развития от кучи проводов и изоленты, развешенных по стенам, до вполне приличного, на мой взгляд, результата.

Все сервисы написаны на языке С++ с использованием фреймворка [Qt5](https://doc.qt.io/qt-5) и общаются друг с другом посредством MQTT-брокера. Выглядит это приблизительно вот так:

[![HOMEd Diagram](assets/images/homed-diagram.png)](assets/images/homed-diagram.png)

## Сервисы

- [HOMEd ZigBee](/zigbee/)
- [HOMEd Modbus](/modbus/)
- [HOMEd Custom](/custom/)
- [HOMEd Automation](/automation/)
- [HOMEd Recorder](/recorder/)
- [HOMEd Web](/web/)
- [HOMEd Cloud](/cloud/)

## Общие сведения

- [Структура MQTT-топиков](/common/topics.md)
- [Способности устройств](/common/exposes.md)
- [Опции устройств](/common/options.md)

## Оборудование

- [HOMEd Gateway Nano](/hardware/nano.md)
- [HOMEd Gateway Pico](/hardware/pico.md)

## Прочее

- [Home Assistant Add-ons](/other/addons.md)
- [HOMEd Lua](/other/lua.md)
- [Сборник пользовательских рецептов](https://community.homed.dev)
- [Канал проекта в Telegram](https://t.me/homed_info)
