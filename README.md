NerdMiner_v2_8bit_LCD

The following is the startup connection screen
![image](images/1716025051557.jpg)

I use the Wemos D1 R32 board with UNO's dedicated 8bit parallel LCD, which just allows me to easily connect the wiring between the ESP32 board and the LCD.
![image](images/1716025051575.jpg)
![image](images/1716025051566.jpg)

Using the Wemos D1 R32 board requires some modifications. Refer to the TFT_espi [here](https://github.com/Bodmer/TFT_eSPI?tab=readme-ov-file#8-bit-parallel-support)) instructions and solder 3 jumpers on the back of the ESP32 board.

Known issues: This board only has a reset button and no other buttons to switch screen functions.
