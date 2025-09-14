# ZigBee: Компиляция исходного кода

# Компиляторы

Данные компиляторы [GCC](ttps://ru.wikipedia.org/wiki/GNU_Compiler_Collection) предназначены для работы в среде `Linux` на процессорах с архитектурой `amd64`.

| Компилятор | Целевая платформа |
|----------- |-------------------|
| [gcc-aarch64-none-linux-gnu-10.2.0.tar.xz](https://sandbox.u236.org/toolchain/gcc/gcc-aarch64-none-linux-gnu-10.2.0.tar.xz)                                         | Linux (aarch64) |
| [gcc-arm-linux-gnuebihf-9.4.0.tar.xz](https://sandbox.u236.org/toolchain/gcc/gcc-arm-linux-gnuebihf-9.4.0.tar.xz)                                                   | Linux (armhf) |
| [gcc-aarch64_generic-openwrt-linux-8.4.0-musl.tar.xz](https://sandbox.u236.org/toolchain/gcc/gcc-aarch64_generic-openwrt-linux-8.4.0-musl.tar.xz)                   | OpenWRT (aarch64_generic) |
| [gcc-arm_cortex-a7_neon-vfpv4-openwrt-linux-8.4.0-musl.tar.xz](https://sandbox.u236.org/toolchain/gcc/gcc-arm_cortex-a7_neon-vfpv4-openwrt-linux-8.4.0-musl.tar.xz) | OpenWRT (arm_cortex-a7_neon-vfpv4) |
| [gcc-arm_cortex-a9_neon-openwrt-linux-8.4.0-musl.tar.xz](https://sandbox.u236.org/toolchain/gcc/gcc-arm_cortex-a9_neon-openwrt-linux-8.4.0-musl.tar.xz)             | OpenWRT (arm_cortex-a9_neon) |
| [gcc-mips_24kc-openwrt-linux-8.4.0-musl.tar.xz](https://sandbox.u236.org/toolchain/gcc/gcc-mips_24kc-openwrt-linux-8.4.0-musl.tar.xz)                               | OpenWRT (mips_24kc) |
| [gcc-mipsel_24kc-openwrt-linux-8.4.0-musl.tar.xz](https://sandbox.u236.org/toolchain/gcc/gcc-mipsel_24kc-openwrt-linux-8.4.0-musl.tar.xz)                           | OpenWRT (mipsel_24kc) |
| [gcc-aarch64-openwrt-linux-gnu-8.4.0.tar.xz](https://sandbox.u236.org/toolchain/gcc/gcc-aarch64-openwrt-linux-gnu-8.4.0.tar.xz)                                     | Entware (aarch64) |
| [gcc-mips-openwrt-linux-gnu-8.4.0.tar.xz](https://sandbox.u236.org/toolchain/gcc/gcc-mips-openwrt-linux-gnu-8.4.0.tar.xz)                                           | Entware (mips) |
| [gcc-mipsel-openwrt-linux-gnu-8.4.0.tar.xz](https://sandbox.u236.org/toolchain/gcc/gcc-mipsel-openwrt-linux-gnu-8.4.0.tar.xz)                                       | Entware (mipsel) |

## Готовые сборки _Qt 5_

Данные сборки [Qt5](https://doc.qt.io/qt-5) предназначены для использования в среде `Linux` на процессорах с архитектурой `amd64`.

| Сборка | Целевая платформа |
|--------|-------------------|
| [qt-amd64-linux-5.15.4-shared.tar.xz](https://sandbox.u236.org/toolchain/qt/qt-amd64-linux-5.15.4-shared.tar.xz)                                                       | Linux (amd64) |
| [qt-aarch64-linux-gnu-5.15.4-shared.tar.xz](https://sandbox.u236.org/toolchain/qt/qt-aarch64-linux-gnu-5.15.4-shared.tar.xz)                                           | Linux (aarch64) |
| [qt-arm-linux-gnueabihf-5.15.4-share.tar.xz](https://sandbox.u236.org/toolchain/qt/qt-arm-linux-gnueabihf-5.15.4-shared.tar.xz)                                        | Linux (armhf) |
| [qt-aarch64_generic-openwrt-linux-5.15.4-shared.tar.xz](https://sandbox.u236.org/toolchain/qt/qt-aarch64_generic-openwrt-linux-5.15.4-shared.tar.xz)                   | OpenWRT (aarch64_generic) |
| [qt-arm_cortex-a7_neon-vfpv4-openwrt-linux-5.15.4-shared.tar.xz](https://sandbox.u236.org/toolchain/qt/qt-arm_cortex-a7_neon-vfpv4-openwrt-linux-5.15.4-shared.tar.xz) | OpenWRT (arm_cortex-a7_neon-vfpv4) |
| [qt-arm_cortex-a9_neon-openwrt-linux-5.15.4-shared.tar.xz](https://sandbox.u236.org/toolchain/qt/qt-arm_cortex-a9_neon-openwrt-linux-5.15.4-shared.tar.xz)             | OpenWRT (arm_cortex-a9_neon) |
| [qt-mips_24kc-openwrt-linux-5.15.4-shared.tar.xz](https://sandbox.u236.org/toolchain/qt/qt-mips_24kc-openwrt-linux-5.15.4-shared.tar.xz)                               | OpenWRT (mips_24kc) |
| [qt-mipsel_24kc-openwrt-linux-5.15.4-shared.tar.xz](https://sandbox.u236.org/toolchain/qt/qt-mipsel_24kc-openwrt-linux-5.15.4-shared.tar.xz)                           | OpenWRT (mipsel_24kc) |
| [qt-aarch64-openwrt-linux-gnu-5.15.4-shared.tar.xz](https://sandbox.u236.org/toolchain/qt/qt-aarch64-openwrt-linux-gnu-5.15.4-shared.tar.xz)                           | Entware (aarch64) |
| [qt-mips-openwrt-linux-gnu-5.15.4-shared.tar.xz](https://sandbox.u236.org/toolchain/qt/qt-mips-openwrt-linux-gnu-5.15.4-shared.tar.xz)                                 | Entware (mips) |
| [qt-mipsel-openwrt-linux-gnu-5.15.4-shared.tar.xz](https://sandbox.u236.org/toolchain/qt/qt-mipsel-openwrt-linux-gnu-5.15.4-shared.tar.xz)                             | Entware (mipsel) |


## Компиляция _Qt 5_

Минимальный набор исходников Qt 5 для сборки приложений _HOMEd_, собранный из официального пакета `qt-everywhere-opensource-src-5.15.4.tar.xz`, включающий в себя модуль [qtmqtt](https://github.com/qt/qtmqtt) и несколько исправлений: [qt-src-5.15.4-homed-minimal.tar.xz](https://sandbox.u236.org/toolchain/qt-src-5.15.4-homed-minimal.tar.xz)

#### Подготовка к компиляции

```sh
./configure -v
  -opensource \
  -confirm-license \
  -release \
  -optimize-size \
  -shared \
  -prefix /my/qt/location \
  -xplatform my-qt-target \
  -c++std c++17 \
  -no-gui \
  -no-widgets \
  -no-opengl \
  -no-sql-sqlite2 \
  -no-sql-psql \
  -no-sql-mysql \
  -no-sql-odbc \
  -no-sql-oci \
  -no-sql-ibase \
  -no-sql-db2 \
  -no-freetype \
  -no-harfbuzz \
  -no-libjpeg \
  -no-libpng \
  -no-zlib \
  -nomake examples \
  -nomake tests
```

| Параметр | Описание |
|----------|----------|
| `-shared`    | динамическая линковка, для статической линковки нужно заменить на `-static` |
| `-prefix`    | путь для установки после компиляции |
| `-xplatform` | целевая платформа |

| Значение `-xplatform` | Целевая платформа |
|----------------------|-------------------|
| `linux-aarch64-gnu-g++`     | Linux (aarch64) |
| `linux-arm-gnueabihf-g++`   | Linux (armhf) |
| `openwrt-aarch64-linux-g++` | OpenWRT (aarch64) |
| `openwrt-arm-linux-g++`     | OpenWRT (arm) |
| `openwrt-i486-linux-g++`    | OpenWRT (i486) |
| `openwrt-mips-linux-g++`.   | OpenWRT (mips) |
| `openwrt-mipsel-linux-g++`  | OpenWRT (mipsel) |
| `entware-aarch64-linux-g++` | Entware (aarch64) |
| `entware-mips-linux-g++`    | Entware (mips) |
| `entware-mipsel-linux-g++`  | Entware (mipsel) |

#### Сборка и установка:

```sh
make -j $(nproc) && make install
```

## Компиляция _HOMEd ZigBee_

```sh
mkdir homed
```

```sh
git clone https://github.com/u236/homed-service-common.git \
  homed/homed-common
```

```sh
git clone https://github.com/u236/homed-serivce-zigbee.git \
  homed/homed-zigbee
```

```sh
cd homed/homed-zigbee
```

```sh
/my/qt/location/bin/qmake homed-zigbee.pro && make -j $(nproc)
```
