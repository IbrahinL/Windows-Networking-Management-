# Windows-Networking-Management-
Windows Networking Management and Configuration. Configuring VPN Connection, Local Firewall Settings, and Configuring TCP/IP Settings on Windows 11.

# Configuring a VPN Connection
This project is a real-world example of configuring a VPN connection. This project simulates a business need to establish a secure connection to the company network to be able to work on the road. In this example, I chose the VPN type that operates using firewall ports that are commonly left open. That also needs to use the most secure password-based authentication possible without a smart card. 

# Add a VPN Connection
<img width="1553" height="832" alt="Screenshot 2026-11-01 092853" src="https://github.com/user-attachments/assets/fee89f02-6786-443d-80a0-b07bf641b0ff" />

# VPN Configuration 
<img width="1558" height="843" alt="Screenshot 2026-11-01 093146" src="https://github.com/user-attachments/assets/8f30ebf9-3901-45c3-b86f-9ad6f09b2672" />

# Setting VPN Security Properties
EAP-MSCHAP v2 is the most secure password-based authentication protocol
<img width="1562" height="822" alt="Screenshot 2026-11-01 093628" src="https://github.com/user-attachments/assets/120ee169-3125-4da2-bbac-c2f19ab35243" />


# Connecting to the VPN
<img width="1502" height="797" alt="Screenshot 2026-11-01 094946" src="https://github.com/user-attachments/assets/b4006371-c624-4cba-86bf-5d0cdc64dd58" />


# Local Firewall Settings
This Project is a real-world example of troubleshooting firewall settings. In this example, the user noticed that Windows Firewall was disabled. The Laptop is currently connected to the organization's network. The user will travel and needs to connect to different Wi-Fi networks. The user needs the firewall to be enabled.

# Turn on Windows Firewall
1. In the Settings app, select Privacy & security, then Windows Security.
2. Select Firewall & Network protection.
3. Turn the firewall on.
<img width="1552" height="831" alt="Screenshot 2026-11-01 114615" src="https://github.com/user-attachments/assets/5b6ebe5e-951b-4ad7-94be-25f14413d0d0" />

<img width="1550" height="820" alt="Screenshot 2026-11-01 114635" src="https://github.com/user-attachments/assets/d6200c17-de76-41c2-806f-d94475a6820c" />

<img width="1452" height="805" alt="Screenshot 2026-11-01 114647" src="https://github.com/user-attachments/assets/bf095c69-3735-4fb7-8a7a-9fb626b8b01f" />


# Allow apps through the public firewall
1. In the Settings app, select Privacy & security, then Windows Security.
2. Select Firewall & Network protection.
3. Select Allow an app through firewall.
4. Select Change settings.
5. Adjust the settings as needed.
<img width="1465" height="778" alt="Screenshot 2026-11-01 114957" src="https://github.com/user-attachments/assets/e33f15f0-bc22-483d-bc09-5809823f90be" />

The apps allowed are: Key Management Service, Cloud Identity, and File and Printer Sharing.

<img width="1557" height="842" alt="Screenshot 2026-11-01 115101" src="https://github.com/user-attachments/assets/815f5f35-509d-4548-8a43-aed57820a1ec" />

# Configuration TCP/IP Settings on Windows 11
In this project, I am simulating being an IT administrator for a small corporate network. One of the computers needs to connect to the local network and the internet using a static IP address.

To access the IPv4 settings:
1. From the Settings app, go to Network & internet, then Advanced network settings.
2. Select More network adapter options.
3. Right-click a connection and select Properties.
4. Select Internet Protocol Version 4, then select Properties.

<img width="1547" height="836" alt="Screenshot 2026-11-01 120729" src="https://github.com/user-attachments/assets/429f2f54-5992-4e5e-8208-babe72b81048" />

<img width="1525" height="817" alt="Screenshot 2026-11-01 120807" src="https://github.com/user-attachments/assets/3ae3bcf6-2cd0-4c49-bdd9-cc513c6b37e8" />

<img width="1497" height="812" alt="Screenshot 2026-11-01 120820" src="https://github.com/user-attachments/assets/4131f5bb-96a7-4093-aaa0-e5c1002a5d07" />

<img width="1548" height="842" alt="Screenshot 2026-11-01 120838" src="https://github.com/user-attachments/assets/96c11f70-2b85-4d4f-990b-70412f555dbf" />

<img width="1532" height="821" alt="Screenshot 2026-11-01 120940" src="https://github.com/user-attachments/assets/c2650cc1-5665-4d81-b5ff-6c93cb2502c1" />
