# Connect to the Modbus device

## FX30 Modbus TCP

Connect a network cable (Cat6 or better) between the FX30 gateway and the controller.

## FX30S Modbus RTU (Serial RS-485)

![RS-485 Serial Interface pin-out ](<../../.gitbook/assets/image (47).png>)

## eXware 703 network interfaces

![](<../../.gitbook/assets/image (68).png>)

Connect a network cable (Cat6 or better) between the eXware 703 and the controller.

Use the ETH1 port (3) to connect to the same network as the Modbus devices.



## eXware 703 serial port



![](<../../.gitbook/assets/image (66).png>)

|   |            |
| - | ---------- |
| 1 | RX/CHB     |
| 2 | TX/CHA     |
| 3 | CTS/CHB+   |
| 4 | RTS/CHA+   |
| 5 | +5V output |
| 6 | GND        |
| 7 |            |
| 8 | SHIELD     |

To operate in RS-485, pins 1-2 and 4-3 must be connected externally.
