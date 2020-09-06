# nmea2000_evb_wifi_eth


this is a fork of https://github.com/AK-Homberger/NMEA2000WifiGateway-with-ESP32

for PlatformIO

ESP32-EVB

ESP32 wifi / BLE development board with Ethernet, relays, microSD card, CAN, infrared, Li-Po charger, GPIOs.

Open-source hardware board made with open-source CAD software. Comes with ESP32-WROOM32 module.

https://www.olimex.com/Products/IoT/ESP32/ESP32-EVB/open-source-hardware

##############################################
CAN
CAN Rx = GPIO 35
CAN Tx = GPIO  5
##############################################

##############################################
MICRO_SD1
GPIO15/HS2_CMD
GPIO14/HS2_CLK
GPIO2/HS2_DATA0
##############################################


##############################################
Relais
GPIO32/REL1
GPIO33/REL2
##############################################

##############################################
Button
EN/But2
GPI34/BUT1
##############################################

##############################################
UEXT
+3.3V               1   2       gnd
GPIO4/U1TXD         3   4       GPI36/U1RXD
GPIO16/I2C-SCL      5   6       GPIO13/I2C-SDA
GPIO15/HS2_CMD      7   8       GPIO2/HS2_DATA0
GPIO14/HS2_CLK      9   10      GPIO17/SPI_CS
##############################################

##############################################
IR
GPIO12/IR_Transmit
GPI39/IR_RECEIVE
##############################################

##############################################
GPIO0/XTAL1/CLKIN           1   2   GPIO1/U0TXD 
GPIO2/HS2_DATA0             3   4   GPIO3/U0RXD 
GPIO4/U1TXD                 5   6   GPIO5/CAN-TX 
GPIO6/SD_CLK                7   8   GPIO7/SD_DATA0 
GPIO8/SD_DATA1              9   10  GPIO9/SD_DATA2
GPIO10/SD_DATA3             11  12  GPIO11/SD_CMD 
GPIO12/IR_Transmit          13  14  GPIO13/I2C-SDA 
GPIO14/HS2_CLK              15  16  GPIO15/HS2_CMD 
GPIO16/I2C-SCL              17  18  GPIO17/SPI_CS 
GPIO18/MDIO(RMII)           19  20  GPIO19/EMAC_TXD0(RMII) 
GPIO21/EMAC_TX_EN(RMII)     21  22  GPIO22/EMAC_TXD1(RMII) 
GPIO23/MDC(RMII)            23  24  GPIO25/EMAC_RXD0(RMII)    
GPIO26/EMAC_RXD1(RMII)      25  26  GPIO27/EMAC_RX_CRS_DV 
GPIO32/REL1                 27  28  GPIO33/REL2 
GPI34/BUT1                  29  30  GPI35/CAN-RX 
GPI36/U1RXD                 31  32  GPI39/IR_RECEIVE
ESP_EN                      33  34  GND 
GND                         35  36  GND 
+3.3V                       37  38  +3.3V 
+5V                         39  40  +5V
##############################################
                            NA(HN2x20)
##############################################


















