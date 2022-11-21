# I2C_scanner_stm32
scaning the I2C bus and getting adresses of conected devices 
![Screenshot 2022-11-21 181225](https://user-images.githubusercontent.com/117598386/203104901-61885eb4-5ca8-4191-8516-9b3d5dab9474.png)
If you have multiple slaves connected through I2C to STM32 
and you need to know their adresses you can scan the I2C Bus 
and get all adresses 

1) Change the #include hal_xxxxxxxxxxx.h depending of your board
2) Upload the soft into the board 
3) Open TeraTerm and connect to the COMx x-the port where your board is connected(TERATERM file)
