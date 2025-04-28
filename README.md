# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP
![Screenshot 2024-09-20 142435](https://github.com/user-attachments/assets/fc11adcc-06ba-4962-a797-e9dc2cb03b05)

## OUPUT - ARP
![Screenshot 2024-09-20 142829](https://github.com/user-attachments/assets/01a7bc41-162f-4cc1-95ef-4d3d13d71f0b)

## PROGRAM - RARP
![Screenshot 2024-09-20 142534](https://github.com/user-attachments/assets/43ac26ae-b308-4e52-98aa-f240230bcba3)

## OUPUT -RARP
![Screenshot 2024-09-20 142839](https://github.com/user-attachments/assets/49ca3427-dfd5-417a-8d40-93721ce86b21)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
