---
uid: Connector_help_Nevion_Flashlink_Frame_-_UDC-HD-XMUX
---

# Nevion Flashlink Frame - UDC-HD-XMUX

This exported connector shows data from a UDX-HD-XMUX module in a Nevion Flashlink frame.

## About

This is an **SNMP** connector that is automatically generated by the parent connector [Nevion Flashlink Frame](xref:Connector_help_Nevion_Flashlink_Frame).

### Version Info

| Range     | Description                                      | DCF Integration     | Cassandra Compliant     |
|------------------|--------------------------------------------------|---------------------|-------------------------|
| 1.0.0.x          | Basic range                                      | No                  | Yes                     |
| 2.0.0.x          | Tree controls added to monitor parameters        | No                  | Yes                     |
| 2.0.1.x          | Audio Block status fix (ONLY for firmware 2.0.4) | No                  | Yes                     |
| 2.0.2.x          | Changed naming structure                         | No                  | Yes                     |

### Product Info

| Range | Supported Firmware Version |
|------------------|-----------------------------|
| 2.0.1.x          | 5.0.4                       |
| 2.0.2.x          | 5.0.4                       |

## Installation and configuration

### Creation

This connector is used by DVE child elements that are **automatically created** by the parent connector [Nevion Flashlink Frame](xref:Connector_help_Nevion_Flashlink_Frame).

## Usage

### General Page

This page contains general information about a UDX-HD-XMUX module, including:

- Type
- Card Status
- Chassis Number
- Slot Number
- Label
- Alarm Status
- Alarm Trap
- Alarm Count
- Main Element Name
- Active Alarms in System

### Audio Page

This page displays the **Audio Block** **Table**, which contains information about all audio I/O blocks.

It also allows you to configure certain parameters, such as **Incoming** and **Outcoming Format**, **SRC**, **Peak** and **Max Level**, **Alarms**, etc.

### Audio Generator Page

This page displays the **Audio Generator** **Table**, which contains information about all audio generators.

You can also configure the Audio **Level** and view the **Audio Generators**.

### Audio Matrix - SDI Outputs Page

This page displays the **Audio Matrix** **Table** and **SDI Outputs Table**. In both tables, you can configure the **Input**.

### Audio Processing - Embedder Page

This page displays the **Audio Proc** **Table**, which contains information about the audio processing capabilities of each card. You can configure the **Mode** and view the **Audio Proc**, **Inputs** and **Outputs**.

This page also displays the **Embedder Table**, which lists all embedders for those modules that have them. You can configure the **Status**, **Word Length**, and **Alarms**, as well as enable or disable the Embedder.

### Changeover Page

This page displays the **Changeover Table**, which contains information about cho1BlockTable parameters.

It also allows you to configure the **Mode**, **Current Input**, **Main**, **Backups**, **Rule**, **Latch**, **Hold** and **Lock Time** and **Alarms**.

### Delay Page

This page displays the **Delay Table**, which contains information about delay parameters.

You can also configure the **Status**, **Lines,** **Samples** and **Nanosecs** delays.

### GPI Matrix Page

This page displays the **GPI Matrix** **Table**, which contains information regarding general purpose interfaces.

### GPIO Page

This page displays the **General Purpose Input Output Table**, which contains information regarding I/O blocks.

You can also configure the **Mode**, **Status**, **Description** and **Alarms**.

### Reclocker Page

This page displays the **Reclocker Table**, which contains information about reclocker parameters.

It also allows you to view the Reclocker **Num**, **Status** and **Bit Rate**, as well as to configure **Config**, **ASI**, **Bandwidth** and **Alarms**.

### Serial Port Page

This page displays the **Serial Port** **Table**, which contains all serial port functions, such as **Mode**, **Status**, **Parity**, **Stopbits**, **Speed**, etc.

### Signal Input Page

This page displays the **EQ Table**, which contains information about EQ parameters.

It also allows you to view the **Num** and **Status**, as well as to configure **Config** and **Alarms**.

### Signal Integrity Page

This page displays the **Monitor** **Table**, which contains information about monitor parameters.

It also allows you to configure **Monitor Alarm**, **Error Count**, **Error Delta** and **Error Free Alarm**, **FF-CRC**, **AP-CRC**, **LOCK**, **ANCS**, etc.

### Sync Source Page

This page displays the **Sync Source** **Table**, which contains information about all sync source inputs.

You can also view the **Sync Src**, **Type**, **Lines**, **Frame Rate** and **Structure**, **Sample Rate** and **Word Length**, as well as configure **Alarms**.

### Video Generator Page

This page displays the **Video Generator** **Table**, which contains information about all video generators.

You can also configure the **Pattern**, **Y**, **Cb** and **Cr**.

### Video Scaler Page

This page displays the **Video Scaler** **Table**, which contains information about all video scalers.

You can also view the **Video Scaler**, **Lines**, **Frame Rate** and **Structure**, **Aspect Ratio**, etc.

### Voltage Page

This page displays the **Voltage Table**, which contains information about voltage measurements.

It also allows you to configure the **Upper** and **Lower Limit** and **Alarms**, as well as to view the **Nominal** effect and the **Value** in Volts and Watts.
