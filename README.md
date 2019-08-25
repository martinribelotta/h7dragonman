# H7-DragonMAN board

STM32H7 LQFP100 board for protocol bridge and industrial control.

## Characterstics:

 - Isolated (see `isolated` branch) and non isolated version
 - STM32H750/743VxTx400MHz in 100LQFP with 8MHz/32.768Khz crystals and ROM Bootloader via USB
 - STM32-based DAP programmer and virtual usb with ROM bootloader via USB
 - External 2/4/8/16MB QSPI flash
 - MicroSD card 1bit slot
 - Two usb otg (FS and HS)
 - 10/100Mb ETH via KSZ8081 in RMII mode
 - RS485 isolated or non-isolated
 - CANBUS isolated or non-isolated
 - Isolated 3.3 to 5V step-up for CANBUS/RS-485 tranceivers
 - One user button
 - One user led
 - 5-24V input via AP63203 DC-DC regulator

## Schematic

![Schematic](docs/dragonmanh7.png)

## Board dimentions

![Outline](docs/pcb-dimentions.png)

## 3D preview

![top](docs/h7-top.png)

![bottom](docs/h7-bottom.png)

![potrail](docs/h7-potrail.png)
