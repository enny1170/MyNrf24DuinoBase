# MyNrf24DuinoBase
Project Template for a MySensors Node based on NRF24Duino from Electrodragon

This is a Arduino Pro mini clone with a NRF24L01 and a Flash-Memory on board.

see https://www.electrodragon.com/w/NRF24L01

buy at https://www.electrodragon.com/product/nrf24duino-arduino-mini-plus-nrf24l01-board/

Uses 
- Mysensors library V 2.3.0
- MySensors NodeManager V 1.7

Precompiled Binarys can be found in the bootloader directory.
Please read the readme in this folder.

Flush this devices with the provided "base" image will turn the device in a Mysensors OTA enabled Node thats also support upload by FTDI.
The Image works on RF Channel 76 (default) and has a static NodeId = 200.
