Reading Speeduino Secondary Serial with broader realtime dataset command "n".
Then passes the data with Realdash CAN to Realdash. Testing has been done with CP21xx UART-USB adapter but should work similarly with HC-05 Bluetooth adapter.  


Code is designed to use ESP32 DEVKIT V1 38PIN Board and 8 channel Optocoupler. And optocoupler is used to input dash warning lights also to the CAN protocol. But you can add what inputs you like.


2SerialToRealdashCAN_confiq.xml

This file is used by Realdash to getting it read the custom channel configuration. Just need to add it in Garage -> Connections -> Realdash CAN -> Custom Channel Description 


Schematic: Coming soon!


This code is based of janimm 'Realdash Arduino CAN example' and pazi88 'Serial3toBMWcan' and modified by paleppp.
