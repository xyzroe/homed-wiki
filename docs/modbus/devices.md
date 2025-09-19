---
title: 'Modbus: Поддержка устройтв'
---

# Modbus: Поддержка устройтв

## Карта регистров

Для декларативного описания [карты регистров](/modbus/database/items/) любых неподдерживаемых устройств необходимсо использовать специальный тип устройства `customController`.

## Фабричные устройства

| Тип устройства | Описание ||
|----------------|----------||
| `r4pin08m0`        | __Eletechsup R4PIN08__         | контроллер ввода/вывода (режим _8DI_) |
| `r4pin08m1`        | __Eletechsup R4PIN08__         | контроллер ввода/вывода (режим _8DO_) |
| `r4pin08m2`        | __Eletechsup R4PIN08__         | контроллер ввода/вывода (режим _4DI-4DO_) |
| `r4pin08m3`        | __Eletechsup R4PIN08__         | контроллер ввода/вывода (режим _2DI-6DO_) |
| `r4pin08m4`        | __Eletechsup R4PIN08__         | контроллер ввода/вывода (режим _6DI-2DO_) |
| `wbM1w2`           | __Wiren Board WB-M1W2__        | датчик температуры |
| `wbMs`             | __Wiren Board WB-MS__          | многофункциональный датчик |
| `wbMsw`            | __Wiren Board WB-MSW__         | многофункциональный датчик |
| `wbMai6`           | __Wiren Board WB-MAI6__        | контроллер аналоговых входов |
| `wbMap3ev`         | __Wiren Board WB-MAP3EV__      | трехфазный вольтметр |
| `wbMap3e`          | __Wiren Board WB-MAP3E__       | счетчик электроэнергии |
| `wbMap6s`          | __Wiren Board WB-MAP6S__       | счетчик электроэнергии |
| `wbMap12e`         | __Wiren Board WB-MAP12E__      | счетчик электроэнергии |
| `wbMap12h`         | __Wiren Board WB-MAP12H__      | счетчик электроэнергии |
| `wbMrwm2`          | __Wiren Board WB-MRWM2__       | модуль реле |
| `wbMrm2`           | __Wiren Board WB-MRM2-mini__   | молуль реле |
| `wbMr3`            | __Wiren Board WB-MR3LV/MRWL3__ | молуль реле |
| `wbMr6`            | __Wiren Board WB-MR6C/MR6-LV__ | молуль реле |
| `wbMr6p`           | __Wiren Board WB-MR6CU/MRPS6__ | молуль реле |
| `wbLed0`           | __Wiren Board WB-LED__         | диммер (режим _W1, W2, W3, W4_) |
| `wbLed1`           | __Wiren Board WB-LED__         | диммер (режим _W1+W2, W3, W4_) |
| `wbLed2`           | __Wiren Board WB-LED__         | диммер (режим _CCT1, W3, W4_) |
| `wbLed16`          | __Wiren Board WB-LED__         | диммер (режим _W1, W2, W3+W4_) |
| `wbLed17`          | __Wiren Board WB-LED__         | диммер (режим _W1+W2, W3+W4_) |
| `wbLed18`          | __Wiren Board WB-LED__         | диммер (режим _CCT1, W3+W4_) |
| `wbLed32`          | __Wiren Board WB-LED__         | диммер (режим _W1, W2, CCT2_) |
| `wbLed33`          | __Wiren Board WB-LED__         | диммер (режим _W1+W2, CCT2_) |
| `wbLed34`          | __Wiren Board WB-LED__         | диммер (режим _CCT1, CCT2_) |
| `wbLed256`         | __Wiren Board WB-LED__         | диммер (режим _RGB, W4_) |
| `wbLed512`         | __Wiren Board WB-LED__         | диммер (режим _W1+W2+W3+W4_) |
| `wbMdm`            | __Wiren Board WB-MDM3__        | силовой диммер |
| `wbUps`            | __Wiren Board WB-UPS v3__      | источник бесперебойгого питания |
| `neptunSmartPlus`  | __Neptun Smart+__              | контроллер защиты от протечек |
| `jth2d1`           | __JTH-2D1__                    | датчик температуры и влажности |
| `t13`              | __T13-750W-12-H__              | частотный преобразователь |
| `m0701s`           | __VFC-M0701S__                 | частотный преобразователь |
