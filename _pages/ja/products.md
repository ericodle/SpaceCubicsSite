---
layout: single
title: "製品"
permalink: /ja/products/
lang: "ja"
---

# CONCEPT

## コスト削減と信頼性

宇宙機器の開発では、予算が限られているため、安価な汎用コンピュータを採用することがありますが、放射線が非常に強い宇宙空間での動作に対する信頼性に不安が残るかもしれません。信頼性を高めるためには、放射線耐性が高い部品が搭載されたコンピュータを採用する選択肢がありますが、これらの製品は高価格であり、かつ製品を購入するだけでは宇宙でのミッションで起こる全てのトラブルを解決できるわけではありません。

## Space Cubicsは、低コストでありながら、宇宙機器に必要な高い信頼性を持つ製品を提供します。

## 耐障害性

一般に、ほとんどの高信頼性コンピュータには耐障害性機能が標準で備わっていません。

たとえ放射線耐性が高い部品が搭載されているコンピュータでも、強い放射線によって引き起こされる障害（記憶されているデータが化けてしまうなど）が起こることがあります。宇宙機器の場合、ハードウェアに障害が発生しても部品交換はできず、またソフトウェアの問題でも地上から復旧は困難です。

Space Cubicsの製品は障害は必ず起こるものだという前提のもと、障害からの速やかな復旧が重要だという考えに基づき、多くの耐障害性機能を備えています。例えば、コンピュータを複数台同時に稼働・連携することで冗長性を持たせたり、データ異常が発生することを想定して同じデータを複数個所に保存し、多数決でデータの正当性を判定する機能を備えているので、障害が発生したコンピュータやデータを自動で復旧することができます。

## 使いやすさ

Space Cubicsの製品の最も良いところは、ユーザーがミッションに必要な機能の開発だけに専念することができることです。我々の製品には、耐障害性機能以外にも、宇宙機器でよく使用されるミドルウェアやプロトコル(ISS互換ネットワークプロトコル、TTEthernet、cFSなど)や、宇宙以外の分野でよく使われているROS(Robot Operating System)などもサポートします。また、ソフトウェアやハードウェア(CPUボード、FPGA)のカスタム開発やコンサルティングも承ります。

## Space Cubicsは低価格な宇宙用コンピュータと宇宙開発に関するトータルサポートを提供することで、宇宙開発への参入を手軽にし、日本はもとよりアジアを中心とした民間の宇宙産業発展に貢献します。


<div style="float: left; margin-left: 20px;">
  <img src="/assets/imgs/products_pcb1.webp" alt="Space Bedroom" width="1000">
</div>


# PRODUCTS

## Command & Data Handling
## Onboard Computer (OBC)

JAXAが国際宇宙ステーションで培った信頼性設計技術を基にキューブサット用に最適設計した宇宙用コンピュータです。Xilinx製 Artix-7 FPGAを採用し、インターフェースの種類や数をユーザ毎に柔軟に対応することができます。キューブサット以外の宇宙機や地上の産業用途にも使用可能です。


# SPECIFICATION

## SC-OBC Module A1
 メインFPGAデバイス
 Xilinx Artix-7

## Partial Reconfiguration/Triple Modular Redundancy
 クロック発信器
 24 MHz x 2

## Redundancy
 メインCPU
 ARM Cortex M3 (Soft Core)
 オペレーティングシステム
 Zephyr RTOS

## Zephyr webサイトはこちら
 異常検知／システムリカバリ用PIC
 8 Bit PIC MCU
 オンチップSRAM
 64 kByte FPGA Block RAM

## ECC and Memory Scrubbing
 オンボードSRAM
 4 MByte
 コンフィギュレーション用NOR Flashメモリ
 32 MByte x 2

## Redundancy
 データ用NOR Flashメモリ
 32 MByte x 2

## Redundancy
 FeRAM
 512 kByte x 2

## Redundancy
 通信インタフェース
 CAN, I2C, UART
 FPGA User I/O
 38 pin
 PIC User I/O
 3 pin
 温度センサー
 3
 ウォッチドッグタイマ
 1 (IP Core)
 インタフェースコネクタ
 80 pin/0.5mmピッチ
 電源電圧
 DC 5.0V ± 10%

## Input Power Line Redundancy with Current & Voltage Monitor
消費電力
2.0 W (Max)
使用温度範囲
-40 〜 +80 ℃ (TBD)
外形寸法
70 x 70 x 9.6 mm
質量
130 g
価格
SC-OBC Module A1

## 30万円（税別）

## 本価格は期間限定の特別価格となります（価格適用の条件はこちら）
## インタフェースボード受託開発
## お問合せ下さい

## SC-OBC Module A1と衛星を接続するための基板開発を受託します


## 価格に関する注意事項

### SC-OBC Module A1（以下、「本製品」と表記します）は自社開発衛星による宇宙実証を予定しております。本価格は宇宙実証までの期間限定の特別価格となります。


## 特別価格が適用される条件は以下のとおりです。

本製品を購入いただいたことを弊社ホームページやSNS等で公開することを許諾いただきます
本製品を使用した機器を宇宙へ打上げた実績、あるいは地上産業において使用された実績を弊社ホームページやSNS等で公開することを許諾いただきます
本製品を宇宙で使用した際の運用データを提供いただきます（データは公開いたしません。また、今後の製品仕様へのフィードバックが目的のため、本製品の機能性能に関わるデータのみの提供を希望しております。データ提供の範囲や提供方法など、ご不明な点がございましたらお問合せ下さい。）
本製品の使い勝手や仕様への要望等についてアンケートにご協力いただく場合がございます


# データシート
# ユーザーマニュアル

SC-OBC Module A1の仕様、通信系統、回路構成等について記載されています。
Link
FPGAハードウェアマニュアル

SC-OBC Module A1に搭載されているFPGAの仕様書です。FPGAの開発や、ソフトウェアの開発に必要な、FPGA機能に関する仕様やレジスタの仕様が記載されています。
Link
Github

その他、様々な技術情報はこちらを参照ください。
LINK
Notice

現在開発中のため仕様は予告なく変更となる可能性があります。 

ユーザーのご要望を多く取り入れたいためリクエストがある方は是非お問合せ下さい。

# 使用例

<div style="float: left; margin-left: 20px;">
  <img src="/assets/imgs/products_pcb2.webp" alt="Space Bedroom" width="500">
</div>

弊社人工衛星に搭載するため、PC104形状に合わせたインタフェースボードの上にSC-OBC Module A1を搭載した形態

<div style="float: left; margin-left: 20px;">
  <img src="/assets/imgs/products_tower.webp" alt="Space Bedroom" width="500">
</div>

インタフェースボードに搭載したSC-OBC Module A1が組み込まれた人工衛星（写真は開発中のもの）