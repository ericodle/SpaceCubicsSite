---
layout: products
title: "Products"
permalink: /en/products/
lang: "en"
---

<section class="page__hero" style="position: relative; background-image: url('/assets/imgs/products_banner.jpeg'); background-size: cover; background-position: center; height: 20vh; display: flex; align-items: center; justify-content: center; width: 100%; margin: 0; overflow: hidden;">
  <div class="overlay" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0, 0, 0, 0.7);"></div>
  <div class="wrapper" style="text-align: center; color: white; width: 100%; height: 100%; display: flex; align-items: center; justify-content: center; position: relative;">
    <h1>CONCEPT</h1>
  </div>
</section>


  <!-- Field 1: CONCEPT -->
<div class="midline_container" id="concept">
  <h3 class="concept_heading">Cost Savings and Reliability</h3>
    <p>In space equipment development, budgets are often limited, leading to the use of inexpensive general-purpose computers. However, concerns about their reliability in the harsh conditions of outer space, where radiation levels are extremely high, remain.</p>
    <p>One way to improve reliability is to use computers with radiation-resistant components, but these products are costly. Additionally, purchasing such equipment alone does not address all the challenges that arise during a space mission.</p>
    <p>Space Cubics offers cost-effective products that maintain the high reliability needed for space equipment.</p>
  <h3 class="concept_heading">Fault Tolerance</h3>
    <p>In general, most high-reliability computers do not include built-in fault tolerance features.</p>
    <p>Even if a computer is equipped with radiation-resistant components, strong radiation can still cause damage, such as data corruption. In space, if a hardware failure occurs, the parts cannot be replaced, and software issues are difficult to resolve remotely from the ground.</p>
    <p>Space Cubics' products are designed with numerous fault-tolerant features, based on the understanding that failures are inevitable and that quick recovery is crucial. For example, we can implement redundancy by running and linking multiple computers simultaneously, or by storing identical data in multiple locations to protect against data corruption. A majority vote system can then be used to verify the validity of the data. These features enable automatic recovery of both computers and data in the event of a failure.</p>
  <h3 class="concept_heading">Ease of Use</h3>
    <p>The greatest advantage of Space Cubics' products is that users can focus exclusively on developing the mission-specific features.</p>
    <p>In addition to fault tolerance functions, our products come with middleware and protocols commonly used in space equipment, such as ISS-compatible network protocols, TTEthernet, and cFS. We also support ROS (Robot Operating System), which is widely used in industries beyond space. Additionally, we offer custom development and consulting services for both software and hardware, including CPU boards and FPGAs.</p>
    <p>By offering affordable space computers and comprehensive space development support, Space Cubics simplifies entry into space development and contributes to the growth of the private space industry in Japan and across Asia.</p>
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
      <p style="font-size: 40px"> This space computer is optimally designed for CubeSats, leveraging reliability design technology developed by JAXA for the International Space Station. Featuring Xilinx's Artix-7 FPGA, it offers flexible support for various interface types and quantities, tailored to each user's needs. It is also suitable for use in spacecraft beyond CubeSats, as well as for ground-based industrial applications.</p>
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
        <p class="spec_heading">Main FPGA Device</p>
        <small>Partial Reconfiguration/Triple Modular Redundancy</small>
      </div>
      <div class="column">
        <p class="spec_heading">Xilinx Artix-7</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">Clock Oscillator</p>
        <small>Redundancy</small>
      </div>
      <div class="column">
        <p class="spec_heading">24 MHz x 2</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">Main CPU</p>
      </div>
      <div class="column">
        <p class="spec_heading"> ARM Cortex M3 (Soft Core)</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">Operating System</p>
        <small><a href="https://docs.zephyrproject.org/latest/boards/arm/scobc_module1/doc/index.html">Zephyr website</a></small>
      </div>
      <div class="column">
        <p class="spec_heading">Zephyr RTOS</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">PIC for anomaly detection/system recovery</p>
      </div>
      <div class="column">
        <p class="spec_heading">8 Bit PIC MCU</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">On-chip SRAM</p>
        <small>ECC and Memory Scrubbing</small>
      </div>
      <div class="column">
        <p class="spec_heading">64 kByte FPGA</p>
        <p class="spec_heading">Block RAM</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">NOR Flash memory for configuration</p>
        <small>Redundancy</small>
      </div>
      <div class="column">
        <p class="spec_heading">32 MByte x 2</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">NOR Flash memory for data</p>
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
        <p class="spec_heading">Communication Interface</p>
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
        <p class="spec_heading">Temperature Sensor</p>
      </div>
      <div class="column">
        <p class="spec_heading">3</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">Watchdog Timer</p>
      </div>
      <div class="column">
        <p class="spec_heading">1 (IP Core)</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">Interface Connector</p>
      </div>
      <div class="column">
        <p class="spec_heading">80 pin/0.5mm pitch</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">Power Supply Voltage</p>
        <small>Input Power Line Redundancy with Current & Voltage Monitor</small>
      </div>
      <div class="column">
        <p class="spec_heading">DC 5.0V ± 10%</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">Power Consumption</p>
      </div>
      <div class="column">
        <p class="spec_heading">2.0 W (Max)</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">Operating Temperature Range</p>
      </div>
      <div class="column">
        <p class="spec_heading">-40 to +80 ℃ (TBD)</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">External Dimensions</p>
      </div>
      <div class="column">
        <p class="spec_heading">70 x 70 x 9.6 mm</p>
      </div>
    </div>
    <div class="row">
      <div class="column">
        <p class="spec_heading">Mass</p>
      </div>
      <div class="column">
        <p class="spec_heading">130 g</p>
      </div>
    </div>
  <div class="divider"></div>
    <h3 class="manager_heading">Price</h3>
    <div class="row">
      <div class="column">
        <p class="manager_heading">SC-OBC Module A1</p>
        <small>This price is a special price for a limited time (Click here for conditions of price application)</small>
      </div>
        <div class="column">
          <p class="manager_heading">JPY 300,000（excluding tax）</p>
        </div>
      </div>
    <div class="row">
      <div class="column">
        <p class="manager_heading">Interface board contract development</p>
        <small>We develop boards that link the SC-OBC Module A1 to satellites.</small>
      </div>
        <div class="column">
          <p class="manager_heading">Please contact us for more details.</p>
        </div>
      </div>
    </div>
  </div>

<!-- Field 4: data notes -->
<div class="midline_container" id="datanotes">
  <h2 class="heading">Notes on Pricing</h2>
  <div class="divider"></div>
    <div class="midline_container">
      <p>The SC-OBC Module A1 is planned for space demonstration aboard a satellite developed in-house. The listed price is a special, limited-time offer available only until the space demonstration.</p>
      <p>The special price is subject to the following conditions:</p>
      <ul>
        <li>We kindly request your permission to publish details of your purchase of this product on our website, social media platforms, and other channels.</li>
        <li>Additionally, we seek your consent to share the outcomes of devices utilizing this product, whether launched into space or applied in terrestrial industries, on our website, social media, and similar outlets.</li>
        <li>We kindly request you to provide operational data from the use of this product in space. This data will remain confidential and will only include information related to the functionality and performance of this product. The purpose is to gather feedback for improving future product specifications.</li>
        <li>If you have any questions about the scope of the data request or the process for providing it, please feel free to contact us.</li>
        <li>We may request your participation in a survey to gather feedback on the usability and specifications of this product.</li>
      </ul>
    </div>
  </div>

<!-- Field 5: data sheet -->
<div class="midline_container" id="datasheet">
  <h2 class="heading">Data Sheets</h2>
  <div class="divider"></div>
    <div class="midline_container">
      <h3 class="manager_heading">User Manual</h3>
        <p>Describes specifications, communication system, circuit configuration, etc. for SC-OBC Module A1.</p>
          <a href="your-url-here" style="text-decoration: none;">
            <button style="padding: 10px 20px; font-size: 16px; border: 1px solid #000; background-color: #fff; cursor: pointer;">LINK</button>
          </a>
      <h3 class="manager_heading">FPGA Hardware Manual</h3>
        <p>This is the specification sheet for the FPGA installed in the SC-OBC Module A1. It includes details on FPGA functions and register specifications essential for FPGA and software development.</p>
          <a href="your-url-here" style="text-decoration: none;">
            <button style="padding: 10px 20px; font-size: 16px; border: 1px solid #000; background-color: #fff; cursor: pointer;">LINK</button>
          </a>
      <h3 class="manager_heading">GitHub</h3>
        <p>For additional technical information, please refer to this resource.</p>
          <a href="your-url-here" style="text-decoration: none;">
            <button style="padding: 10px 20px; font-size: 16px; border: 1px solid #000; background-color: #fff; cursor: pointer;">LINK</button>
          </a>
      <div style="text-align: center;">
        <h3>Notice</h3>
        <p>The product is currently under development, and specifications are subject to change without notice.</p>
        <p>We aim to incorporate as many user requests as possible. If you have any suggestions or requests, please don't hesitate to contact us.</p>
        <a href="your-url-here" style="text-decoration: none;">
          <button style="padding: 10px 20px; font-size: 16px; border: 1px solid #000; background-color: #fff; cursor: pointer;">Contact</button>
        </a>
      </div>
  </div>

<!-- Field 6: example -->
<div class="midline_container" id="example">
  <h2 class="heading">Example Use Case</h2>
  <div class="divider"></div>
  <div class="example-row" style="display: flex; justify-content: space-between;">
    <div class="column" style="flex: 1; margin-right: 10px;">
      <img src="/assets/imgs/products_pcb2.webp" alt="" width="500">
      <p>To be installed on our satellite, the SC-OBC Module A1 is mounted on an interface board designed to match the PC104 form factor.</p>
    </div>
    <div class="column" style="flex: 1; margin-left: 10px;">
      <img src="/assets/imgs/products_tower.webp" alt="" width="500">
      <p>The satellite with the SC-OBC Module A1 installed on the interface board (currently in development).</p>
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