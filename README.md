# How Establish Connection between NRF and PiCo


## Components used in this project
1. RPi Pico Wireless or without
2. Female and Male Jumpper connector
3. NRF receiver and transmitter
4. Breadboard for device placement

## Schematic used in this project
* PiCo ----- NRF
* 3V3 ----- VCC
* GND ----- GND
* GP16 -----MISO
* GP19 -----MOSI
* GP18 -----SCK
![PiCO_Connections](https://user-images.githubusercontent.com/81543946/219866848-5d727f0e-4274-4cfd-a1ad-0342e7305d2c.png)


## How to run this code
1. Upload transmitter and reciver code into PiCo. Please ensure correct CE an CSN pin match to hardware connection
2. Go to "RPi_Pico_Keyboard_Send_To_NRF_Transmitter_Python" directory and run python script with admin access
- > sudo python3.8 RPI_Pico_Send_Data_To_NRF.py
- > **Hint: ** Please ensure serial port in python script match to transmitter serial address
3. At this step, the code should work.
4. Please ensure data is received on receiver side

