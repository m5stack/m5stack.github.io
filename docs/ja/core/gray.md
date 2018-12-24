# M5Stack GRAY

<img src="assets/img/product_pics/core/gray/gray_01.png" alt="gray_02" width="250" height="250"> <img src="assets/img/product_pics/core/gray/gray_02.png" alt="gray_02" width="250" height="250"> <img src="assets/img/product_pics/core/gray/gray_04.png" alt="gray_04" width="65%" height="65%">

* * *

:memo:**[概要](#概要)**&nbsp;&nbsp;&nbsp;:bulb:**[クイックスタート](ja/quick_start/m5core/m5stack_core_quick_start)**&nbsp;&nbsp;&nbsp;:octocat:**[サンプルコード](https://github.com/m5stack/M5Stack/tree/master/examples/Basics)**&nbsp;&nbsp;&nbsp;:electric_plug:**[回路図](https://github.com/m5stack/M5-3D_and_PCB/blob/master/M5_Core_SCH%2820171206%29.pdf)**&nbsp;&nbsp;&nbsp;🛒**[購入リンク](https://www.aliexpress.com/store/product/M5Stack-Official-In-Stock-ESP32-Mpu9250-9Axies-Motion-Sensor-Core-Development-Kit-Extensible-IoT-Development-Board/3226069_32836393710.html?spm=2114.12010615.8148356.12.25e96be7zRik8r.html)**&nbsp;&nbsp;&nbsp;:clapper:**[関連動画](#関連動画)**

## 概要

**<mark>M5Stack GRAY</mark>**は**ESP32**チップがベースです。**Blockly**、**Arduino**、**MicroPython**などでプログラミングすることができます。

**M5Stack GRAY**はESP32プログラミングに必要なものに加えて、**MPU9250**MEMSセンサー（3軸ジャイロ + 3軸加速度 + 3軸地磁気)、TFT LCDなどを備えています。簡易版"Leap Motion"のような3Dリモートジェスチャーコントローラなどを短時間で作ることが出来るでしょう。

ボトムボードはDIY用のI2Sピン(GPIO0, GPIO12, GPIO13, GPIO15, GPIO34)の他に、M-Bus上のGPIOを拡張利用できるようにデザインされています。

## 特徴

- プログラミングサポート
  - Arduino
  - ESP-IDF
  - MicroPython
- [TFカード](https://ja.wikipedia.org/wiki/SD%E3%83%A1%E3%83%A2%E3%83%AA%E3%83%BC%E3%82%AB%E3%83%BC%E3%83%89)サポート

## スペック

|項目|詳細|
|:---|:---|
|ESP32| 240MHz x 2 コア, 600 DMIPS, 520KB SRAM, Wi-Fi, デュアルモード Bluetooth|
|Flash| 4MB |
|電源入力| 5V @ 500mA|
|インターフェース| USB Type-C x 1, Grove(I2C+I/0+UART) x 1|
|画面| 2 inch, 320x240 Colorful TFT LCD, ILI9342 |
|スピーカー| 1W-0928 |
|MEMS| MPU9250 |
|電池| 150mAh @ 3.7V, inside 内蔵|
|動作温度| 32°F to 104°F ( 0°C to 40°C ) |
|サイズ| 54 x 54 x 12.5 mm |
|ケース| プラスチック ( PC ) |
|重量| 120g (ボトムモジュール含む), 100g (コアのみ)|

## ピンマップ

**Speaker**

| Speak Pin | ESP32 Chip |
|:----------|:-----------|
| Speak Pin | GPIO25     |

**Button**

| Button Pin | ESP32 Chip |
|:-----------|:-----------|
| BUTTON A   | GPIO39     |
| BUTTON B   | GPIO38     |
| BUTTON C   | GPIO37     |

**IMUセンサー**

| MPU9250 | ESP32 Chip |
|:--------|:-----------|
| SCL     | GPIO22     |
| SDA     | GPIO21     |

**GROVE**

| Port A(I2C) | ESP32 Chip |
|:------------|:-----------|
| SCL         | GPIO22     |
| SDA         | GPIO21     |
| 5V          | 5V         |
| GND         | GND        |

**LCD**

| ILI9341 | ESP32 Chip |
|:--------|:-----------|
| MOSI    | GPIO23     |
| MISO    | /          |
| CLK     | GPIO18     |
| CS      | GPIO14     |
| DC      | GPIO27     |
| RST     | GPIO33     |
| BL      | GPIO32     |

**TFカード**

| TFCard Pin | ESP32 Chip |
|:-----------|:-----------|
| MOSI       | GPIO23     |
| MISO       | GPIO19     |
| CLK        | GPIO18     |
| CS         | GPIO4      |

**M-Bus**

<figure>
  <img src="assets/img/product_pics/core/M-BUS.png" alt="M_BUS" width="300px" height="300px">
</figure>

## パッケージ内容

- 1x M5Stack GRAY
- 1x M5Stack ボトムモジュール
- USB Type-C ケーブル
- ユーザーマニュアル

## ドキュメント

- **データシート**
  - [ESP32](https://www.espressif.com/sites/default/files/documentation/esp32_datasheet_cn.pdf)
  - [MPU9250](https://www.invensense.com/wp-content/uploads/2015/02/PS-MPU-9250A-01-v1.1.pdf)

## 関連動画

- **m5stackの紹介**

<iframe width="560" height="315" src="https://www.youtube.com/embed/W5ZfDCBc1lk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>