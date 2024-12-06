---
layout: products
title: "製品"
permalink: /ja/products/
lang: "ja"
---

<!-- Banner -->
<section class="page__hero" style="position: relative; background-image: url('/assets/imgs/products_banner.jpeg'); background-size: cover; background-position: center; height: 20vh; display: flex; align-items: center; justify-content: center; width: 100%; margin: 0; overflow: hidden;">
  <div class="overlay" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0, 0, 0, 0.7);"></div>
  <div class="wrapper" style="text-align: center; color: white; width: 100%; height: 100%; display: flex; align-items: center; justify-content: center; position: relative;">
    <h1>CONCEPT</h1>
  </div>
</section>

# コスト削減と信頼性

### 宇宙機器の開発では、予算が限られているため、安価な汎用コンピュータを採用することがありますが、放射線が非常に強い宇宙空間での動作に対する信頼性に不安が残るかもしれません。

### 信頼性を高めるためには、放射線耐性が高い部品が搭載されたコンピュータを採用する選択肢がありますが、これらの製品は高価格であり、かつ製品を購入するだけでは宇宙でのミッションで起こる全てのトラブルを解決できるわけではありません。

<br><br>

# 耐障害性

### 一般に、ほとんどの高信頼性コンピュータには耐障害性機能が標準で備わっていません。

### たとえ放射線耐性が高い部品が搭載されているコンピュータでも、強い放射線によって引き起こされる障害（記憶されているデータが化けてしまうなど）が起こることがあります。宇宙機器の場合、ハードウェアに障害が発生しても部品交換はできず、またソフトウェアの問題でも地上から復旧は困難です。

### Space Cubicsの製品は障害は必ず起こるものだという前提のもと、障害からの速やかな復旧が重要だという考えに基づき、多くの耐障害性機能を備えています。例えば、コンピュータを複数台同時に稼働・連携することで冗長性を持たせたり、データ異常が発生することを想定して同じデータを複数個所に保存し、多数決でデータの正当性を判定する機能を備えているので、障害が発生したコンピュータやデータを自動で復旧することができます。

<br><br>

# 使いやすさ

### Space Cubicsの製品の最も良いところは、ユーザーがミッションに必要な機能の開発だけに専念することができることです。

### 我々の製品には、耐障害性機能以外にも、宇宙機器でよく使用されるミドルウェアやプロトコル(ISS互換ネットワークプロトコル、TTEthernet、cFSなど)や、宇宙以外の分野でよく使われているROS(Robot Operating System)などもサポートします。また、ソフトウェアやハードウェア(CPUボード、FPGA)のカスタム開発やコンサルティングも承ります。

### Space Cubicsは低価格な宇宙用コンピュータと宇宙開発に関するトータルサポートを提供することで、宇宙開発への参入を手軽にし、日本はもとよりアジアを中心とした民間の宇宙産業発展に貢献します。

<br><br>

<!-- Banner -->
<section class="page__hero" style="position: relative; background-image: url('/assets/imgs/products_banner2.jpeg'); background-size: cover; background-position: center; height: 20vh; display: flex; align-items: center; justify-content: center; width: 100%; margin: 0; overflow: hidden;">
  <div class="overlay" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0, 0, 0, 0.7);"></div>
  <div class="wrapper" style="text-align: center; color: white; width: 100%; height: 100%; display: flex; align-items: center; justify-content: center; position: relative;">
    <h1>PRODUCTS</h1>
  </div>
</section>

<br><br>

# Onboard Computers (OBC) for Command & Data Handling <img src="/assets/imgs/products_pcb1.webp" alt="" style="float: left; margin: 20px; width: 800px;">

### JAXAが国際宇宙ステーションで培った信頼性設計技術を基にキューブサット用に最適設計した宇宙用コンピュータです。Xilinx製 Artix-7 FPGAを採用し、インターフェースの種類や数をユーザ毎に柔軟に対応することができます。キューブサット以外の宇宙機や地上の産業用途にも使用可能です。

<br><br>

## Product Specifications
### SC-OBC Module A1

  | Specification                          | Details                                      |
  |----------------------------------------|----------------------------------------------|
  | **Main FPGA Device (Partial Reconfiguration/Triple Modular Redundancy)**                   | Xilinx Artix-7                               |
  | **Clock Oscillator (redundant)**                   | 24 MHz x 2                                   |
  | **Main CPU**                           | ARM Cortex M3 (Soft Core)                    |
  | **Operating System [Zephyr](https://docs.zephyrproject.org/latest/boards/arm/scobc_module1/doc/index.html)**                   | Zephyr RTOS                                  |
  | **PIC for anomaly detection/system recovery** | 8 Bit PIC MCU                         |
  | **On-chip SRAM**                       | 64 kByte FPGA                                |
  | **ECC and Memory Scrubbing**           | Block RAM                                    |
  | **NOR Flash memory for configuration (redundant)** | 32 MByte x 2                                 |
  | **NOR Flash memory for data (redundant)**          | 32 MByte x 2                                 |
  | **FeRAM (redundant)**                              | 512 kByte x 2                                |
  | **Communication Interface**            | CAN, I2C, UART                               |
  | **FPGA User I/O**                      | 38 pin                                       |
  | **PIC User I/O**                       | 3 pin                                        |
  | **Temperature Sensor**                 | 3                                            |
  | **Watchdog Timer**                     | 1 (IP Core)                                  |
  | **Interface Connector**                | 80 pin/0.5mm pitch                           |
  | **Power Supply Voltage (Input Power Line Redundancy with Current & Voltage Monitor)**               | DC 5.0V ± 10%                                |
  | **Power Consumption**                  | 2.0 W (Max)                                  |
  | **Operating Temperature Range**        | -40 to +80 ℃ (TBD)                          |
  | **External Dimensions**                | 70 x 70 x 9.6 mm                             |
  | **Mass**                               | 130 g                                        |

  Price

  | Item                                    | Price                                        |
  |-----------------------------------------|----------------------------------------------|
  | **SC-OBC Module A1**                    | JPY 300,000（excluding tax）                 |
  | **This is a limited time price** | [Click here for conditions of price application](#) |
  | **Interface board contract development** | Please contact us for more details.          |
  | **We also develop boards that link the SC-OBC Module A1 to satellites.** | |

<br><br>

# 価格に関する注意事項

### SC-OBC Module A1（以下、「本製品」と表記します）は自社開発衛星による宇宙実証を予定しております。本価格は宇宙実証までの期間限定の特別価格となります。

### 特別価格が適用される条件は以下のとおりです。

- 本製品を購入いただいたことを弊社ホームページやSNS等で公開することを許諾いただきます。
- 本製品を使用した機器を宇宙へ打上げた実績、あるいは地上産業において使用された実績を弊社ホームページやSNS等で公開することを許諾いただきます。
- 本製品を宇宙で使用した際の運用データを提供いただきます。
- 本製品の使い勝手や仕様への要望等についてアンケートにご協力いただく場合がございます。
- データは公開いたしません。また、今後の製品仕様へのフィードバックが目的のため、本製品の機能性能に関わるデータのみの提供を希望しております。
- データ提供の範囲や提供方法など、ご不明な点がございましたらお問合せ下さい。

<br><br>

# データシート
## ユーザーマニュアル
### SC-OBC Module A1の仕様、通信系統、回路構成等について記載されています。
[LINK](http://www.url.here)

## FPGAハードウェアマニュアル
### SC-OBC Module A1に搭載されているFPGAの仕様書です。FPGAの開発や、ソフトウェアの開発に必要な、FPGA機能に関する仕様やレジスタの仕様が記載されています。
[LINK](http://www.url.here)

## GitHub
### その他、様々な技術情報はこちらを参照ください。
[LINK](http://www.url.here)

## **Note:**
### 現在開発中のため仕様は予告なく変更となる可能性があります。
### ユーザーのご要望を多く取り入れたいためリクエストがある方は是非お問合せ下さい。
[LINK](http://www.url.here)

# 使用例
### <img src="/assets/imgs/products_pcb2.webp" alt="" style="fixed: left; margin: 20px; width: 700px;"> 
### 弊社人工衛星に搭載するため、PC104形状に合わせたインタフェースボードの上にSC-OBC Module A1を搭載した形態。

### <img src="/assets/imgs/products_tower.webp" alt="" style="fixed: right; margin: 20px; width: 700px;"> 
### インタフェースボードに搭載したSC-OBC Module A1が組み込まれた人工衛星（写真は開発中のもの）。
