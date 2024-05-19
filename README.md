# NerdMiner_v2_8bit_LCD

![image](images/1716025051557.jpg)

## Hardware Configuration

I use the Wemos D1 R32 board along with a dedicated 8-bit parallel LCD for the UNO, which allows for easy wiring connections between the ESP32 board and the LCD.

![image](images/1716025051575.jpg)

## Necessary Modifications

Using the Wemos D1 R32 board requires some modifications. Please refer to the [TFT_eSPI instructions](https://github.com/Bodmer/TFT_eSPI?tab=readme-ov-file#8-bit-parallel-support) and solder 3 jumpers on the back of the ESP32 board.
![image](images/1716025051566.jpg)

## Software Configuration

All TFT LCD settings are configured in the `platformio.ini` file, so make sure to clear all settings in `User_Setup.h` in the TFT_eSPI library folder.

## Known Issues

The Wemos D1 R32 board has only a reset button and no additional buttons for switching screen functions.

[![Watch the video](images/1716025051557.jpg)](https://www.youtube.com/watch?v=WJxXGNcD-kI)
https://www.youtube.com/watch?v=WJxXGNcD-kI
