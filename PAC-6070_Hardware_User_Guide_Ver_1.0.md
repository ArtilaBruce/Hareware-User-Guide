PAC-6070

Programmable Automation Controller

Hardware User Guide

Beta Version 1.0

Copyright © Artila Electronics Co., Ltd.  All Rights Reserved.

Table of Contents

# Introduction

The PAC-6070 is a cost-effective Linux computing platform powered by Cortex-A7 MPU. It offers a versatile range of on-board IOs, including voltage/current measurement, opto-isolated digital inputs, and high-power relay outputs.  With its comprehensive IO capabilities, the PAC-6070 enables efficient monitoring and control, making it the perfect choice for advanced Industrial IoT applications.

PAC-6070 is powered by NXP i.MX6ULL Cortex-A7 Processor with 1GB SDRAM and 16GB eMMC. PAC-6070 features 5 A/D channels：3 channels differential input mode (Voltage) and 2 channels single-end input mode (Current)，8 channels digital inputs, and 8 x relay outputs. In addition, PAC-6070 integrates two 10/100Mbps Ethernet, one isolated RS-485 ports, one USB host, one MicroSD socket, and one miniPCIe slot. The DIN-Rail also makes PAC-6070’s onsite installation flexible.

## Features

Cost-Effective Linux Computing Platform

Rugged Design for Industrial Automation Application

NXP i.MX6ULL Arm Cortex-A7 CPU, up to 800MHz

1GB LvDDR3 SDRAM, 16GB eMMC

8 x Relay Outputs

8 x Opto-Isolated Digital Inputs

5 x 24-bits A/D Channels

1 x Full Size miniPCIe Socket & 1 x Micro-SIM Slot

1 x Micro-SD Card Socket

2 x 10/100Mbps Ethernet Interface

1 x USB port

1 x RS-485 Serial Port

+9~+48 VDC Wide-Range Power Input

Dimension: 121.8mm x 204mm x 50mm (4.8" x 8" x1.96")

Easy for DIN-Rail Mounting

## Packing List

PAC-6070 Programmable Automation Controller

## Optional Accessory

4G/LTE miniPCIe Module with Antenna

Wi-Fi miniPCIe Module with Antenna

# Layout: Diagram and M/B photo

M/B Photo

Dimensions (WxLxH): 121.8 x 204 x 50mm (4.8 x 8 x 1.96in)

Net Weight: 360g (0.791b)

Operating Temperature: 0~70°C (32~158°F)

# Pin Assignment and Definition

## Reset Button

The PAC 6070 provides a multi-function reset button location shown below:

.

The behavior of the reset button depends on how long you press the reset button.

## Power LED

The Power LED will show solid green if power is properly applied.

## Ready LED

After PAC-6070 is power on, the Ready LED will show solid orange if PAC-6070 complete system boots up.  If Ready LED is off during system boot up, please check if power input is correct.  Turn off the power and restart PAC-6070 again.  If Ready LED is still off, please contact the manufacturer for technical support.

## LAN1 / LAN2 LED

When Ethernet ports are connected to the network, Link/Act will show solid green and if there is traffic in the Ethernet, this LED will flash.

## Serial Port LED

## 

One dual color LEDs indicate the data traffic at the serial ports. Dual color LEDs indicate the data traffic at the serial ports. When the RXD line is high then green light is ON and when the TXD line is high, yellow light is ON.

## Ethernet Port (LAN1 / LAN2)

## 

## Serial Port

RS-485 (Data+, Data-)

Data+ is pull up to V_ISO with 1K Ohm resistor. Data- is pull low to ground.  The PAC-6070 provides on-board 120Ohm termination resistor for each RS-485 port.

Termination resistor is not included.	If want to enable the termination resistor, please adjust the associated jumper to short as below.  User can add a 120 Ohm resistor shunt with D+ to D- if necessary.                                                            Jumper

## 3.8 Serial Console Port ：Debug Port（ RS-232 with RxD, TxD ）

There is a 4-pin wafer box header (J4) inside the PAC-6070 features as serial console port that used for locally accessing PAC-6070 system via console port.

The Pin assignments are RX, TX, +3.3V, GND.

## 

## 

## Power Input Connector (CN1)

PAC-6070 uses +9VDC to 48VDC power and input from CN1 connector.	.

## Relay Output

8 x relay output channels

Contact Rating: /

Max. Switching Voltage: 125VAC / 60VDC

Max. Switching Current: 2A

Jumper setting : The default jumper setting of Relay Output is NO

Pin assignment of Digital Output

Reference Circuit as follows:

## Digital Input Connector

The 8 channel isolated input are equipped with 5000Vrms photo coupler isolator.	Four of the channels form a group and share the same common ground.	The specifications of the isolated input channels are:

Logical High: 5~24Vdc Logical Low: 0~1.5Vdc

Input resistance: 1.8KOhms @0.5W Response time: 20µs

Isolation: 5000Vrms

DIx: Isolated digital input channels，COMx: common ground of four DIx

Pin assignment of Digital Input

DI 1~4

ICOM1

DIx: Isolated digital input channels. COM: Common ground.

## Analog Input Connector

Each of the 5 channels isolated analog input can be configured as various input ranges and the common features are show as follows:

Effective Resolution: 24-bit

Channels: differential input channels Input Mode (Voltage): 3 channels (diﬀerential input )

Input Range (Voltage): +/- 10VDC

(Optional) 2 x Single-end channels, call for driver support

Input Mode (Current): 2 channels (single-end) Input Current: 0~20mA

Jumper

## Jumper11 location (red arrow) and Jumper 11 Setting

## MiniPCIe Slot

The PAC 6070 includes a miniPCIe slot, accessible by following the direction of the red arrow shown below.

The PAC-6070 supports wireless connectivity options.  The device is compatible with both WiFi and LTE modules. We have certified several modules for use, including:

• SIM7600 (LTE)
• RYWDB00 (WiFi + Bluetooth)

For detailed specifications and compatibility information, please refer to the following:

## 

3.14  Nano-SIM card socket

There is an internal Nano-SIM card socket that is available for use with an LTE/4G module.  Please put  SIM card on tray holder and inserted by following the instructions shown below.

## 

## 3.15  SD card Socket

There is an internal micro-SD card socket for data storage, accessible by following the red arrow direction shown below.

## 

## Jumper Setting and Jumper location (red arrow)

## 

## 

