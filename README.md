# Shake Psoc6

In this project a Psoc 6 with a 028 TFT shield is used to measure the accelerometer values. the data is send and received via UDP.

when the Psoc starts it will send 'A' to the server(or any device you want to connect to the Psoc)

the server then sends a value from 1-100 wich is the time in seconds the psoc will be measuring the shaking.
After this time has passed the psoc will send the shake value in a string(asci) back to the server.

## How to use

Change WIFI_SSID and WIFI_PASSWORD to the name and password of your wifi network in udp_client.h  
![image](./wifi.png)   

Change UDP_SERVER_IP_ADDRESS and UDP_SERVER_PORT to the ip and port of your server in udp_client.h   
![image](./server.png)  


##Example
![video](example.MOV)


https://user-images.githubusercontent.com/69217508/159126515-e50976c9-af8f-44a0-b190-e4efb69d2e54.MOV


