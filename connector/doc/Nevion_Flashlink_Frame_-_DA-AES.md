---
uid: Connector_help_Nevion_Flashlink_Frame_-_DA-AES
---

# Nevion Flashlink Frame - DA-AES

This exported connector shows data from a DA-AES module in a Nevion Flashlink frame.

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

This page contains general information about a DA-AES module, including:

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

### Voltage Page

This page displays the **Voltage Table**, which contains information about voltage measurements.

It also allows you to configure the **Upper** and **Lower Limit** and **Alarms**, as well as to view the **Nominal** effect and the **Value** in Volts and Watts.

### Audio Page

This page displays the **Audio Block** **Table**, which contains information about all audio I/O blocks.

It also allows you to configure certain parameters, such as **Incoming** and **Outcoming Format**, **SRC**, **Peak** and **Max Level**, **Alarms**, etc.

### Audio Matrix - SDI Outputs Page

This page displays the **Audio Matrix** **Table**, as well as the **SDI Outputs Table**. In both of these tables, the **Input** can be configured.
