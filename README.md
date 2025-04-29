# CHIRIMEN と Raspberry Pi Zero W で始めるセンサー制御入門

## 本書について

本書は、各種センサーを使った電子工作やプログラミングに興味のある方のための技術同人誌です。  
Raspberry Pi と温度・湿度・加速度などのセンサーを組み合わせて、実際に動かすためのサンプルコードや解説を掲載しています。

### 本書の特徴

- **初心者でも安心**
  - センサーの接続方法や開発環境のセットアップ手順を、写真や図を交えて丁寧に解説しています。
- **すぐに試せるサンプルコード**
  - 各センサーごとに、動作確認済みのサンプルコードを掲載。コピー＆ペーストですぐに動かせます。
- **実践的な活用例**
  - 実際のプロジェクトで役立つ、センサーの組み合わせ例や応用アイデアも紹介しています。

#### こんな方におすすめ

- 電子工作や IoT に興味がある方
- Raspberry Pi を使ってみたい方
- センサーの使い方を基礎から学びたい方
- 実践的なサンプルコードを探している方

### 前提条件

本書は、下記環境での使用を想定しています。

#### デバイス

- Raspberry Pi Zero **`W`**
- `Wi-fi 搭載モデル`の Raspberry Pi Zero です。
- 購入先
  - KSY：[Raspberry Pi Zero WH [RASPIZWHSC0065]](https://raspberry-pi.ksyic.com/main/index/pdp.id/406,407,408,409,410,219,222/pdp.open/219)
  - SWITCH SCIENCE：[Raspberry Pi Zero WH [RPI-ZERO-WH]](https://www.switch-science.com/products/3646?_pos=1&_sid=e9fd90251&_ss=r)

#### Node ライブラリ

- I2C 制御用ライブラリ： [node-web-i2c](https://www.npmjs.com/package/node-web-i2c)
- GPIO 制御用ライブラリ： [node-web-gpio](https://www.npmjs.com/package/node-web-gpio)

#### OS

- Raspbian OS をカスタマイズした [CHIRIMEN Lite](https://github.com/chirimen-oh/chirimen-lite) という OS を使用します。
- OS は、[こちら](https://github.com/chirimen-oh/chirimen-lite/releases)からダウンロードして下さい。

### 直ぐに開発を始めたい方

- [CHIRIMEN Raspberry Pi Zero W チュートリアル](https://tutorial.chirimen.org/pizero/) にアクセスして下さい。
  - [物品準備、PC を WiFi に接続](https://tutorial.chirimen.org/pizero/chapter_2-1)
  - [ターミナル接続](https://tutorial.chirimen.org/pizero/chapter_2-2)
    - [接続先：Pi Zero Web Serial Console](https://chirimen.org/PiZeroWebSerialConsole/PiZeroWebSerialConsole.html)
  - [Pi Zero Web Serial Console の使い方](https://tutorial.chirimen.org/pizero/chapter_2-2-1)
  - [Wi-fi 設定](https://tutorial.chirimen.org/pizero/chapter_2-3)
