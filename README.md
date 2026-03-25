# EXPERIMENT--06-IoT-Based-Relay-Control-System-Using-LoRaWAN-and-Application-Server
## Aim
To configure a LoRaWAN end device and monitor IR sensor data using a network server and dashboard visualization.

## Components Required
- LoRaWAN End Device-STM32
- LoRaWAN Gateway
- Application Server Dashboard
- Serial Port Utility
- Development Tools (STM32CubeIDE, STM32CubeProgrammer)

## Procedure
1. Open STM32CubeIDE and import the project from the realy-control project directory.
2. Select the LoRaWAN End Node project for the NUCLEO-WLE5JC board.
3. Clean all previous build files using the Clean Project option in the build configuration.
4. Build the project to generate the firmware files.
5. Flash the compiled firmware into the STM32 board using STM32CubeProgrammer with baud rate set to 9600.
6. Open the network server console and login using your registered email ID and password.
7. Register the device by selecting Device Types and adding the LoRaWAN device in the network server.
8. Open the Serial Port Utility  give the AT commands and verify device connection through the serial port utility
9. Create a dashboard on the application server by clicking the Add Dashboard option.
10. Add widgets and commands to visualize the relay status data.
11. Send control commands from the dashboard to control the relay.

## Output
### 1. Serial Port Utility – Network Server Connection
<img width="1053" height="658" alt="Screenshot 2026-03-25 155310" src="https://github.com/user-attachments/assets/4348e229-0236-4550-a25e-765ace52372e" />

<img width="1050" height="656" alt="Screenshot 2026-03-25 155327" src="https://github.com/user-attachments/assets/302ed144-6b83-481d-bdeb-4b1b6f73a612" />

<img width="1047" height="655" alt="Screenshot 2026-03-25 155343" src="https://github.com/user-attachments/assets/02961eb8-0349-4600-8798-57729c9ac00e" />

<img width="1046" height="660" alt="Screenshot 2026-03-25 155400" src="https://github.com/user-attachments/assets/b545defc-2b36-46a3-b81d-3f111a8bf4ae" />

<img width="1049" height="657" alt="Screenshot 2026-03-25 155416" src="https://github.com/user-attachments/assets/b4f39824-1a3b-402d-bf5d-1fe76242238f" />


### 2. Network Server – Recent Events
<img width="1046" height="682" alt="Screenshot 2026-03-25 155435" src="https://github.com/user-attachments/assets/ecc988e6-7d10-4886-9398-524ac8594d9d" />


### 3. Dashboard Command Sending
.
### 4. Relay Status Dashboard Output
### Bulb ON → Relay ON 
![Screenshot 2026-03-25 155436](https://github.com/user-attachments/assets/86d39974-6581-4092-b4ba-85fac8004d64)

### Bulb OFF → Relay OFF
<img width="1920" height="1200" alt="Screenshot (49)" src="https://github.com/user-attachments/assets/9f9f2ae1-10fd-4fb8-8c7b-0e824516858b" />


## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
