---
layout: products
title: "製品"
permalink: /ja/products/
lang: "ja"
---

<section class="page__hero" style="position: relative; background-image: url('/assets/imgs/products_banner.jpeg'); background-size: cover; background-position: center; height: 20vh; display: flex; align-items: center; justify-content: center; width: 100%; margin: 0; overflow: hidden;">
  <div class="overlay" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0, 0, 0, 0.7);"></div>
  <div class="wrapper" style="text-align: center; color: white; width: 100%; height: 100%; display: flex; align-items: center; justify-content: center; position: relative;">
    <h1>CONCEPT</h1>
  </div>
</section>

<!-- Field 1: CONCEPT -->
<div class="midline_container" id="concept">
  <h3 class="concept_heading">コスト削減と信頼性</h3>
    <p>宇宙機器の開発では、予算が限られているため、安価な汎用コンピュータを採用することがありますが、放射線が非常に強い宇宙空間での動作に対する信頼性に不安が残るかもしれません。</p>
    <p>信頼性を高めるためには、放射線耐性が高い部品が搭載されたコンピュータを採用する選択肢がありますが、これらの製品は高価格であり、かつ製品を購入するだけでは宇宙でのミッションで起こる全てのトラブルを解決できるわけではありません。</p>
  <h3 class="concept_heading">耐障害性</h3>
    <p>一般に、ほとんどの高信頼性コンピュータには耐障害性機能が標準で備わっていません。</p>
    <p>たとえ放射線耐性が高い部品が搭載されているコンピュータでも、強い放射線によって引き起こされる障害（記憶されているデータが化けてしまうなど）が起こることがあります。宇宙機器の場合、ハードウェアに障害が発生しても部品交換はできず、またソフトウェアの問題でも地上から復旧は困難です。</p>
    <p>Space Cubicsの製品は障害は必ず起こるものだという前提のもと、障害からの速やかな復旧が重要だという考えに基づき、多くの耐障害性機能を備えています。例えば、コンピュータを複数台同時に稼働・連携することで冗長性を持たせたり、データ異常が発生することを想定して同じデータを複数個所に保存し、多数決でデータの正当性を判定する機能を備えているので、障害が発生したコンピュータやデータを自動で復旧することができます。</p>
  <h3 class="concept_heading">使いやすさ</h3>
    <p>Space Cubicsの製品の最も良いところは、ユーザーがミッションに必要な機能の開発だけに専念することができることです。</p>
    <p>我々の製品には、耐障害性機能以外にも、宇宙機器でよく使用されるミドルウェアやプロトコル(ISS互換ネットワークプロトコル、TTEthernet、cFSなど)や、宇宙以外の分野でよく使われているROS(Robot Operating System)などもサポートします。また、ソフトウェアやハードウェア(CPUボード、FPGA)のカスタム開発やコンサルティングも承ります。</p>
    <p>Space Cubicsは低価格な宇宙用コンピュータと宇宙開発に関するトータルサポートを提供することで、宇宙開発への参入を手軽にし、日本はもとよりアジアを中心とした民間の宇宙産業発展に貢献します。</p>
</div>


<!-- Photo Section -->
<section class="page__hero" style="position: relative; background-image: url('/assets/imgs/products_banner2.jpeg'); background-size: cover; background-position: center; height: 20vh; display: flex; align-items: center; justify-content: center; width: 100%; margin: 0; overflow: hidden;">
  <div class="overlay" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0, 0, 0, 0.7);"></div>
  <div class="wrapper" style="text-align: center; color: white; width: 100%; height: 100%; display: flex; align-items: center; justify-content: center; position: relative;">
    <h1>PRODUCTS</h1>
  </div>
</section>


<!-- Field 2: OBC -->
<div class="midline_container" id="Onboard Computer (OBC)">
  <h2 class="heading">Onboard Computers (OBC) for Command & Data Handling</h2>
  <div class="divider"></div>
  <div class="row">
    <div class="left_justify">
      <div style="float: left; margin-left: 10px;">
        <img src="/assets/imgs/products_pcb1.webp" alt="" width="1200">
      </div>
    </div>
    <div class="lowered_column">
      <p style="font-size: 40px"> JAXAが国際宇宙ステーションで培った信頼性設計技術を基にキューブサット用に最適設計した宇宙用コンピュータです。Xilinx製 Artix-7 FPGAを採用し、インターフェースの種類や数をユーザ毎に柔軟に対応することができます。キューブサット以外の宇宙機や地上の産業用途にも使用可能です。</p>
    </div>
  </div>
</div>

<!-- Field 3: specs -->
<div class="midline_container" id="specs">
  <h2 class="heading">Product Specifications</h2>
  <div class="divider"></div>
  <div class="midline_container">
    <h3 class="manager_heading">SC-OBC Module A1</h3>
    <div class="row">
      <div class="column">
        <p class="spec_heading">メインFPGAデバイス</p>
        <small>Partial Reconfiguration/Triple Modular Redundancy</small>
      </div>
      <div class="column">
        <p class="spec_heading">Xilinx Artix-7</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">クロック発信器</p>
        <small>Redundancy</small>
      </div>
      <div class="column">
        <p class="spec_heading">24 MHz x 2</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">メインCPU</p>
      </div>
      <div class="column">
        <p class="spec_heading"> ARM Cortex M3 (Soft Core)</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">オペレーティングシステム</p>
        <small><a href="https://docs.zephyrproject.org/latest/boards/arm/scobc_module1/doc/index.html">Zephyr webサイトはこちら</a></small>
      </div>
      <div class="column">
        <p class="spec_heading">Zephyr RTOS</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">異常検知／システムリカバリ用PIC</p>
      </div>
      <div class="column">
        <p class="spec_heading">8 Bit PIC MCU</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">オンチップSRAM</p>
        <small>ECC and Memory Scrubbing</small>
      </div>
      <div class="column">
        <p class="spec_heading">64 kByte FPGA</p>
        <p class="spec_heading">Block RAM</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">コンフィギュレーション用NOR Flashメモリ</p>
        <small>Redundancy</small>
      </div>
      <div class="column">
        <p class="spec_heading">32 MByte x 2</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">データ用NOR Flashメモリ</p>
        <small>Redundancy</small>
      </div>
      <div class="column">
        <p class="spec_heading">32 MByte x 2</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">FeRAM</p>
        <small>Redundancy</small>
      </div>
      <div class="column">
        <p class="spec_heading">512 kByte x 2</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">通信インタフェース</p>
      </div>
      <div class="column">
        <p class="spec_heading">CAN, I2C, UART</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">FPGA User I/O</p>
      </div>
      <div class="column">
        <p class="spec_heading">38 pin</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">PIC User I/O</p>
      </div>
      <div class="column">
        <p class="spec_heading">3 pin</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">温度センサー</p>
      </div>
      <div class="column">
        <p class="spec_heading">3</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">ウォッチドッグタイマ</p>
      </div>
      <div class="column">
        <p class="spec_heading">1 (IP Core)</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">インタフェースコネクタ</p>
      </div>
      <div class="column">
        <p class="spec_heading">80 pin/0.5mmピッチ</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">電源電圧</p>
        <small>Input Power Line Redundancy with Current & Voltage Monitor</small>
      </div>
      <div class="column">
        <p class="spec_heading">DC 5.0V ± 10%</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">消費電力</p>
      </div>
      <div class="column">
        <p class="spec_heading">2.0 W (Max)</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">使用温度範囲</p>
      </div>
      <div class="column">
        <p class="spec_heading">-40 〜 +80 ℃ (TBD)</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">外形寸法</p>
      </div>
      <div class="column">
        <p class="spec_heading">70 x 70 x 9.6 mm</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">質量</p>
      </div>
      <div class="column">
        <p class="spec_heading">130 g</p>
      </div>
    </div>
  <div class="divider"></div>
    <h3 class="manager_heading">価格</h3>
    <div class="row">
      <div class="column">
        <p class="manager_heading">SC-OBC Module A1</p>
        <small>本価格は期間限定の特別価格となります（以下の価格適用条件を参照してください）</small>
      </div>
        <div class="column">
          <p class="manager_heading">30万円（税別）</p>
        </div>
      </div>
    <div class="row">
      <div class="column">
        <p class="manager_heading">インタフェースボード受託開発</p>
        <small>SC-OBC Module A1と衛星を接続するための基板開発を受託します</small>
      </div>
        <div class="column">
          <p class="manager_heading">お問合せ下さい</p>
        </div>
      </div>
    </div>
  </div>

<!-- Field 4: data notes -->
<div class="midline_container" id="datanotes">
  <h2 class="heading">価格に関する注意事項</h2>
  <div class="divider"></div>
    <div class="midline_container">
      <p>SC-OBC Module A1（以下、「本製品」と表記します）は自社開発衛星による宇宙実証を予定しております。本価格は宇宙実証までの期間限定の特別価格となります。</p>
      <p>特別価格が適用される条件は以下のとおりです。</p>
      <ul>
        <li>本製品を購入いただいたことを弊社ホームページやSNS等で公開することを許諾いただきます。</li>
        <li>本製品を使用した機器を宇宙へ打上げた実績、あるいは地上産業において使用された実績を弊社ホームページやSNS等で公開することを許諾いただきます。</li>
        <li>本製品を宇宙で使用した際の運用データを提供いただきます。</li>
        <li>本製品の使い勝手や仕様への要望等についてアンケートにご協力いただく場合がございます。</li>
        <li>データは公開いたしません。また、今後の製品仕様へのフィードバックが目的のため、本製品の機能性能に関わるデータのみの提供を希望しております。</li>
        <li>データ提供の範囲や提供方法など、ご不明な点がございましたらお問合せ下さい。</li>
      </ul>
    </div>
  </div>


<!-- Field 5: data sheet -->
<div class="midline_container" id="datasheet">
  <h2 class="heading">データシート</h2>
  <div class="divider"></div>
    <div class="midline_container">
      <h3 class="manager_heading">ユーザーマニュアル</h3>
        <p>SC-OBC Module A1の仕様、通信系統、回路構成等について記載されています。</p>
          <a href="your-url-here" style="text-decoration: none;">
            <button style="padding: 10px 20px; font-size: 16px; border: 1px solid #000; background-color: #fff; cursor: pointer;">LINK</button>
          </a>
      <h3 class="manager_heading">FPGAハードウェアマニュアル</h3>
        <p>SC-OBC Module A1に搭載されているFPGAの仕様書です。FPGAの開発や、ソフトウェアの開発に必要な、FPGA機能に関する仕様やレジスタの仕様が記載されています。</p>
          <a href="your-url-here" style="text-decoration: none;">
            <button style="padding: 10px 20px; font-size: 16px; border: 1px solid #000; background-color: #fff; cursor: pointer;">LINK</button>
          </a>
      <h3 class="manager_heading">GitHub</h3>
        <p>その他、様々な技術情報はこちらを参照ください。</p>
          <a href="your-url-here" style="text-decoration: none;">
            <button style="padding: 10px 20px; font-size: 16px; border: 1px solid #000; background-color: #fff; cursor: pointer;">LINK</button>
          </a>
      <div style="text-align: center;">
        <h3>Notice</h3>
        <p>現在開発中のため仕様は予告なく変更となる可能性があります。</p>
        <p>ユーザーのご要望を多く取り入れたいためリクエストがある方は是非お問合せ下さい。</p>
        <a href="your-url-here" style="text-decoration: none;">
          <button style="padding: 10px 20px; font-size: 16px; border: 1px solid #000; background-color: #fff; cursor: pointer;">お問い合わせ</button>
        </a>
      </div>
  </div>

<!-- Field 6: example -->
<div class="midline_container" id="example">
  <h2 class="heading">使用例</h2>
  <div class="divider"></div>
  <div class="example-row" style="display: flex; justify-content: space-between;">
    <div class="column" style="flex: 1; margin-right: 10px;">
      <img src="/assets/imgs/products_pcb2.webp" alt="" width="500">
      <p>弊社人工衛星に搭載するため、PC104形状に合わせたインタフェースボードの上にSC-OBC Module A1を搭載した形態。</p>
    </div>
    <div class="column" style="flex: 1; margin-left: 10px;">
      <img src="/assets/imgs/products_tower.webp" alt="" width="500">
      <p>インタフェースボードに搭載したSC-OBC Module A1が組み込まれた人工衛星（写真は開発中のもの）。</p>
    </div>
  </div>
</div>

<style>
  .heading {
    font-size: 3em; /* Adjust the size as needed */
    color: gray;
  }
  .subheading {
    font-size: 2em; /* Adjust the size as needed */
    color: gray;
  }
  .concept_heading {
    font-size: 1.5em; /* Adjust the size as needed */
    color: black;
  }
  .left_justify {
    text-align: left;
    margin: 50px;
  }
  .divider {
    height: 2px;
    background-color: gray;
    margin: 10px 0;
  }
  .content-container {
    width: 100%;
  }
  .midline_container {
    width: 80%;
    margin: 0 auto;
  }
  .field {
    margin-bottom: 20px;
  }
  .row {
    display: flex;
  }
  .column {
    flex: 1;
    padding: 5px;
  }
  .lowered_column {
    flex: 1;
    padding: 50px;
    margin-top: 100px;
  }
  .centered_column {
    flex: 1;
    text-align: center;
  }
  .column.right.no-divider {
    border-left: none;
  }
  .manager_heading {
    font-size: 1.5em; /* Adjust the size as needed */
    color: black;
  }
  .spec_heading {
    font-size: 1em; /* Adjust the size as needed */
    color: black;
  }
small {
  display: block;
  font-size: 0.8em;
  color: #666;
}
</style>