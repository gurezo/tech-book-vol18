# CHIRIMEN と Raspberry Pi Zero W で始めるセンサー制御入門

## 本書について

本書は、各種センサーを使った電子工作やプログラミングに興味のある方のための技術同人誌です。  
Raspberry Pi や Arduino などの開発ボードと、温度・湿度・加速度などのセンサーを組み合わせて、実際に動かすためのサンプルコードや解説を掲載しています。

### 本書の特徴

- **初心者でも安心**
  - センサーの接続方法や開発環境のセットアップ手順を、写真や図を交えて丁寧に解説しています。
- **すぐに試せるサンプルコード**
  - 各センサーごとに、動作確認済みのサンプルコードを掲載。コピー＆ペーストですぐに動かせます。
- **実践的な活用例**
  - 実際のプロジェクトで役立つ、センサーの組み合わせ例や応用アイデアも紹介しています。

#### こんな方におすすめ

- 電子工作や IoT に興味がある方
- Raspberry Pi や Arduino を使ってみたい方
- センサーの使い方を基礎から学びたい方
- 実践的なサンプルコードを探している方

### 前提条件

本書は、下記環境での使用を想定しています。

#### デバイス

- Raspberry Pi Zero **`W`**
- `Wi-fi 搭載モデル`の Raspberry Pi Zero です。

#### Node ライブラリ

- I2C 制御用ライブラリ： [node-web-i2c](https://www.npmjs.com/package/node-web-i2c)
- GPIO 制御用ライブラリ： [node-web-gpio](https://www.npmjs.com/package/node-web-gpio)

#### OS

- Rasbian OS をカスタマイズした [chrimen-lite](https://github.com/chirimen-oh/chirimen-lite) という OS を使用します。
- OS は、[こちら](https://github.com/chirimen-oh/chirimen-lite/releases)からダウンロードして下さい。

### 直ぐに開発を始めたい方

- [CHIRIMEN Raspberry Pi Zero W チュートリアル](https://tutorial.chirimen.org/pizero/) にアクセスして下さい。
  - [物品準備、PC を WiFi に接続](https://tutorial.chirimen.org/pizero/chapter_2-1)
  - [ターミナル接続](https://tutorial.chirimen.org/pizero/chapter_2-2)
    - [接続先：Pi Zero Web Serial Console](https://chirimen.org/PiZeroWebSerialConsole/PiZeroWebSerialConsole.html)
  - [Pi Zero Web Serial Console の使い方](https://tutorial.chirimen.org/pizero/chapter_2-2-1)
  - [Wi-fi 設定](https://tutorial.chirimen.org/pizero/chapter_2-3)

## センサー一覧

- [ADDA 変換モジュール ADS1115](./docs/ads1x15.md)
- [ADS1015 12 ビット AD コンバータ](./docs/ads1015.md)
- [ADT7410 温度センサー](./docs/adt7410.md)
- [ADXL345 Grove Accelerometer 3 軸加速度センサー](./docs/adxl345.md)
- [I2C 接続の赤外線測距センサー](./docs/amg8833.md)
- [BH1750 照度センサー](./docs/bh1750.md)
- [BME280 温湿度/気圧センサー](./docs/bme280.md)
- [BMP180 気圧/温度/高度センサー](./docs/bmp180.md)
- [BMP280 気圧/温度センサー](./docs/bmp280.md)
- [GP2Y0E03 測距センサー](./docs/gp2y0e03.md)
- [INA219 使用電流センサー](./docs/ina219.md)
- [MLX90614 赤外線温度センサー](./docs/mlx90614.md)
- [MPR121 Grove Touch Sensor タッチセンサー](./docs/mpr121.md)
- [MPU6050 使用 ３軸ジャイロスコープ/３軸加速度センサー](./docs/mpu6050.md)
- [MPU9250 9 軸ジャイロスコープ加速度計/磁気フィールドセンサー ](./docs/mpu9250.md)
- [neopixel-i2c](./docs/neopixel-i2c.md)
- [PAJ7620U2 Grove Gesture ジェスチャー認識センサー](./docs/paj7620.md)
- [PCA9685 16 チャンネルサーボモーター PWM ドライバー](./docs/pca9685.md)
- [PCF8591 AD/DA 転換モジュール](./docs/pcf8591.md)
- [S11059 デジタルカラーセンサー](./docs/s11059.md)
- [SHT30 温湿度センサー](./docs/sht30.md)
- [SSD1306 OLED ディスプレイ](./docs/ssd1306.md)
- [SSD1308 Grove OLED ディスプレイ](./docs/ssd1308.md)
- [TCS34725 使用 カラーセンサー](./docs/tcs34725.md)
- [TSL2561 Grove Digital Light Sensor 光センサー](./docs/tsl2561.md)
- [VEML6070 UV センサー](./docs/veml6070.md)
- [VL53L0X レーザー測距センサー 30 mm - 2 m](./docs/vl53l0x.md)
- [VL53L1X レーザー測距センサー](./docs/vl53l1x.md)
