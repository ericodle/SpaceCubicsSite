---
layout: products
title: "Products"
permalink: /en/products/
lang: "en"
---

CONCEPT

Cost Savings and Reliability

In space equipment development, budgets are often limited, leading to the use of inexpensive general-purpose computers. However, concerns about their reliability in the harsh conditions of outer space, where radiation levels are extremely high, remain. One way to improve reliability is to use computers with radiation-resistant components, but these products are costly. Additionally, purchasing such equipment alone does not address all the challenges that arise during a space mission.

Space Cubics offers cost-effective products that maintain the high reliability needed for space equipment.


Fault Tolerance

In general, most high-reliability computers do not include built-in fault tolerance features.

Even if a computer is equipped with radiation-resistant components, strong radiation can still cause damage, such as data corruption. 
In space, if a hardware failure occurs, the parts cannot be replaced, and software issues are difficult to resolve remotely from the ground.

Space Cubics' products are designed with numerous fault-tolerant features, based on the understanding that failures are inevitable and that quick recovery is crucial. For example, we can implement redundancy by running and linking multiple computers simultaneously, or by storing identical data in multiple locations to protect against data corruption. A majority vote system can then be used to verify the validity of the data. These features enable automatic recovery of both computers and data in the event of a failure.

Ease of Use

The greatest advantage of Space Cubics' products is that users can focus exclusively on developing the mission-specific features. In addition to fault tolerance functions, our products come with middleware and protocols commonly used in space equipment, such as ISS-compatible network protocols, TTEthernet, and cFS. We also support ROS (Robot Operating System), which is widely used in industries beyond space. Additionally, we offer custom development and consulting services for both software and hardware, including CPU boards and FPGAs.


By offering affordable space computers and comprehensive space development support, Space Cubics simplifies entry into space development and contributes to the growth of the private space industry in Japan and across Asia.


<div style="float: left; margin-left: 20px;">
  <img src="/assets/imgs/products_pcb1.webp" alt="Space Bedroom" width="500">
</div>



# PRODUCTS

Command and Data Handling (C&DH)
Onboard Computer (OBC)

This space computer is optimally designed for CubeSats, leveraging reliability design technology developed by JAXA for the International Space Station. Featuring Xilinx's Artix-7 FPGA, it offers flexible support for various interface types and quantities, tailored to each user's needs. It is also suitable for use in spacecraft beyond CubeSats, as well as for ground-based industrial applications.



# SPECIFICATION

SC-OBC Module A1
Main FPGA device
Xilinx Artix-7

Partial Reconfiguration/Triple Modular Redundancy
clock oscillator
24 MHz x 2

Redundancy
Main CPU
ARM Cortex M3 (Soft Core)
operating system
Zephyr RTOS

Click here for Zephyr website
PIC for anomaly detection/system recovery
8 Bit PIC MCU
On-chip SRAM
64 kByte FPGA Block RAM

ECC and Memory Scrubbing
On-board SRAM
4 MByte
NOR Flash memory for configuration
32 MByte x 2

Redundancy
NOR Flash memory for data
32 MByte x 2

Redundancy
FeRAM
512 kByte x 2

Redundancy
communication interface
CAN, I2C, UART
FPGA User I/O
38 pin
PIC User I/O
3 pin
temperature sensor
3
watchdog timer
1 (IP Core)
interface connector
80 pin/0.5mm pitch
power supply voltage
DC 5.0V ± 10%

Input Power Line Redundancy with Current & Voltage Monitor
Power consumption
2.0 W (Max)
Operating temperature range
-40 〜 +80 ℃ (TBD)
External dimensions
70 x 70 x 9.6 mm
Mass
130 g
price
SC-OBC Module A1
JPY 300,000（excluding tax）

This price is a special price for a limited time (Click here for conditions of price application)
Interface board contract development
Please contact us for more details.

We develop boards that link the SC-OBC Module A1 to satellites.


# Notes on pricing

The SC-OBC Module A1 is planned for space demonstration aboard a satellite developed in-house. 
The listed price is a special, limited-time offer available only until the space demonstration.

The special price is subject to the following conditions:

We kindly request your permission to publish details of your purchase of this product on our website, social media platforms, and other channels.

Additionally, we seek your consent to share the outcomes of devices utilizing this product, whether launched into space or applied in terrestrial industries, on our website, social media, and similar outlets.

We kindly request you to provide operational data from the use of this product in space. This data will remain confidential and will only include information related to the functionality and performance of this product. The purpose is to gather feedback for improving future product specifications.

If you have any questions about the scope of the data request or the process for providing it, please feel free to contact us.

We may request your participation in a survey to gather feedback on the usability and specifications of this product.


# Data sheet
# User manual

Describes specifications, communication system, circuit configuration, etc. for SC-OBC Module A1.
Link
FPGA hardware manual

This is the specification sheet for the FPGA installed in the SC-OBC Module A1. 
It includes details on FPGA functions and register specifications essential for FPGA and software development.
Link
Github

For additional technical information, please refer to this resource.
LINK
Notice

The product is currently under development, and specifications are subject to change without notice.

We aim to incorporate as many user requests as possible. If you have any suggestions or requests, please don't hesitate to contact us.

# Example Use Case

<div style="float: left; margin-left: 20px;">
  <img src="/assets/imgs/products_pcb2.webp" alt="Space Bedroom" width="500">
</div>

# To be installed on our satellite, the SC-OBC Module A1 is mounted on an interface board designed to match the PC104 form factor.

<div style="float: left; margin-left: 20px;">
  <img src="/assets/imgs/products_tower.webp" alt="Space Bedroom" width="500">
</div>

# The satellite with the SC-OBC Module A1 installed on the interface board (currently in development).