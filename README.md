# NUCLEO-STM32F439ZI-TCP-CLIENT-LwIP-TEST
-This is an application design to send data to UDP client by using LwIP stack.
-Client is your (board) of address 192.168.1.6 and port number=7
-Server is the (Laptop/PC) of address 192.168.1.7 and port number=8

# How to use ?
1)Statically set IP address of your Laptop/PC to 192.168.1.6
2)Download STM32 Cube ide then flash the code on board.
3)Connect the board by ethernet cable directly to your laptop/pc.
4)Download hercules application then set the port number =8 , local port number=7 and module ip = 192.168.1.7.
5)Click listen then test it and enjoy ;) .

# Output ?
-You should see same message "messsge from udp server" followed by a number (counter).
-When you (Laptop/PC) as server send any message this counter is increamented by one with same message showing.
