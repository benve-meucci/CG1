# CryptoGadgets v1

This is a **free and open source project** that let you check the bitcoin price in real time with a small piece of hardware.

Unlike similar devices this one uses WebSockets and updates the display real-time, several time per second!

I first created these objects for myself, playing with 3D modeling and ESP32 software development.

https://github.com/giovantenne/CG1/assets/917400/3fa1b79c-759e-4132-b921-984ed2b7a950


## Features

- WiFi powered. No PC needed
- True real-time price
- Display up to 9 digits
- Adjustable display brightness
- 24h price change
- Support for more than 600 pairs
- Upgradable firmware

## User manual

This is a stand-alone device. This means that you don’t need a PC  to get it running and that you can simply power it through the micro-usb port. Before doing so  you will need to connect it to your WiFi network by following these simple steps:

- Power-up your device. When setting it up for the first time, and everytime it is not able to connect to an existing WiFi network, the device will start in “access-point/captive-portal" mode and it will broadcast the WiFi SSID “ToTheMoon”.
- Connect your phone/computer to the “ToTheMoon” WiFi network using the following password: 12345678
- Your phone/computer should prompt you with a login/welcome page. If not you can simply browse to the following address: http://172.217.28.1. You should then be able to see and access the device setup interface.
- On the menu click “Configure new AP”. You should then be presented with a list of existing WiFi networks.
- Click on your network SSID name, enter your passphrase and click “Apply”.


After the first setup, may  you want to change your currency pair, adjust the number of decimal digits or change the display brightness, you can simply browse to the address shown on the display during the booting process after the logo. Before doing so, please ensure  to be connected to the same WiFi network.

You also can easily update the device firmware by downloading the latest version, if needed, from the following link: https://github.com/giovantenne/CG1/releases

You can check the firmware version you are currently running  by simply  looking at the display during the booting process, below the bitcoin logo.


## Setup video tutorial
[![See the video here](https://www.datocms-assets.com/56675/1633985370-pxl20210405091715325-portrait1024x1024.jpg?fm=webp&w=610)](https://www.youtube.com/watch?v=Izq8tlnVEv4)

## Requirements
- Heltec WiFi Kit 32
- 3D BOX [here](stl/)

## Build and load the firmware
- Install PlatformIO Core (https://platformio.org/install/cli)
- Connect the board via USB
- Run `pio run -t upload`

## Donations/Project contributions
If you would like to contribute and help dev team with this project you can send a donation to the following LN address ⚡`donate@btcpay.cryptogadgets.net`⚡ or on-chain   `bc1qg2t8vnahzv5yy7e885l0a59ggagne9nxdvts4t`

If you want to order a fully assembled multipurpose V2 or V3 devices you can contribute to my job at https://www.cryptogadgets.net

Enjoy!
