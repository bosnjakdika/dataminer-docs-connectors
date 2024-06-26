---
uid: Connector_help_AppearTV_X20_Platform_-_AppearTV_X20_Scrambler
---

# AppearTV X20 Platform - AppearTV X20 Scrambler

This connector can be used to view information of **scrambler cards** (CAx100) connected to the AppearTV X20 chassis.

The connector uses an **HTTP** connection. This connection uses the Scrambler API of the CAx100 card to retrieve information from the card and configure settings on the card. The information transfer is performed using JSON.

> [!NOTE]
> This connector is automatically generated by the [AppearTV X20 Platform](xref:Connector_help_AppearTV_X20_Platform) connector, from range 2.0.3.1 onwards.

## About

### Product Info

| Range              | Supported Firmware |
|--------------------|--------------------|
| 2.0.3.x [SLC Main] | -                  |

## Configuration

This connector is **automatically generated** by the parent connector **AppearTV X20 Platform**.

## How to use

The element created with this connector has the following data pages:

- **Scrambling**: Contains a list of all scrambled services for this slot.
- **Alarms**: Lists all alarms related to the scrambling services on this slot.
