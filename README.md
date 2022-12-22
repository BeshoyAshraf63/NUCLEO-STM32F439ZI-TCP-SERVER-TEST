# NUCLEO-STM32F439ZI-TCP-SERVER-LwIP-TEST
-This is an application design to send data/recieve to TCP client by using LwIP stack.\
-SERVER is your (board) of address 192.168.1.7 and port number=7.\
-CLIENT is the (Laptop/PC) of address 192.168.1.6 and port number=8.

# How to use ?
1)Statically set IP address of your Laptop/PC to 192.168.1.6.\
2)Download STM32 Cube ide then flash the code on board.\
3)Connect the board by ethernet cable (RJ45) directly or by switch to your laptop/pc.\
4)Download hercules application then set the port number =7 and module ip = 192.168.1.7.\
5)Click listen then test it and enjoy .\
6)If you send words :\
  a) "data" : the server replies with 50kb of data statically defined with a pointer for testing.\
  b) "red" : the server replies with small msg and red led is toggled.\
  c) "blue" : the server replies with small msg and blue led is toggled.\
  d) "yellow" :the server replies with small msg and yellow led is toggled.

# Output ?
-You should see same message " <ur msg> messsge from server".

