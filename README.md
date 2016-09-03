# esp8266-12reBoard
ESP8266-12 Programming board, 1 sided.  

Having problems flashing your ESP8266-12 board?  I did, thats why I made this board.

This requires a ESP8266-12 already on a breakout board

It has the following:
  microUSB connector (TH)
  5v > 3.3 regulator (SMD)
  On/Off toggle switch (TH)
  104 (10nF) capacitor (TH)
  4.7k pullup resistor connected to GPIO 0 (TH)
  momentary push button to bring GPIO 0 to ground for flashing (TH)
  Place for DS18B20 to hook into GPIO 0 for temperature reading (TH)
  Multiple Terminal connectors for power and grounds (3.3v,5v,GND)
  
  
Uses both Ground Plane fill and no-net-connect fill for minimal etchant used.

Due to it being a one sided board, you will have to run 1 wire on the board to join the ground circuits

It does have .25mm traces, which for some might be difficult.  I suggest people trying the cold toner transfer method using 8parts isopropyl alchohol and 3 parts acetone for transfer, see youtube.  
