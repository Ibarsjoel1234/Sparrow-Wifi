# Sparrow Wifi 

## Deauth using Sparrow-Wifi and MITM using Wifiphisher and Airgeddon

## Description

## DDOS Attack

•	To commence, the initial step involved installing and upgrading Kali Linux through the terminal. Additionally, the sparrow wifi graphical user interface (GUI) tools are implemented to evaluate potential wifi service set identifiers (SSID). 
• This analysis is conducted to identify the target SSID, which is necessary for executing the assault. Furthermore, Sparrow WiFi conducts an analysis of the wireless local area network (WLAN), enabling monitoring and network discovery.  
• In addition to the steps, the user should proceed by choosing the target SSID and subsequently selecting the options for Deauthentication (single) and Deauthentication (continuous). 
• These options effectively result in the expulsion of clients from the wireless network, hence facilitating the successful execution of the Deauthentication Denial-of-Service (DoS) attack.

Deauthentication Broadcast - Single:

![Part-1](https://github.com/Ibarsjoel1234/Sparrow-Wifi/assets/35426719/f5f0433f-1b9b-4639-a76d-ad71cdbd11ab)


Deauthentication Broadcast - Continuous:

![Part - 1 1](https://github.com/Ibarsjoel1234/Sparrow-Wifi/assets/35426719/af670ef6-a386-4c25-9854-df71e41ae1ac)


## Evil Twin Attack - Wifiphiser

• Wifiphisher tools have been used to analyze the possible SSID and select the target SSID. • Next, update the firmware upgrade option and start the attack. When the user tries to connect to the possible wifi (which is unencrypted), it will automatically pop up a notification called Firmware Upgrade with terms and conditions. 
• When the user submits the request, it will capture the user username and password, which will display on the terminal. 

Output:


![Part-2 1](https://github.com/Ibarsjoel1234/Sparrow-Wifi/assets/35426719/9021e081-bcab-43a8-9c58-328320ff370c)


## Evil Twin Attack using WifiPumpkin3 - GUI Format


• Software known as wifipumpkin3 possesses the capability to execute the Deauth Denial-of-Service (DoS) assault. 
• This process encompasses several steps, beginning with the installation of the WiFi Pumpkin program. 
• Subsequently, the Deauth interface is activated, and the BSSID, obtained through scanning, is referenced. 
• Finally, the attack is initiated by executing the START command. This has the potential to render the client device incapable of establishing a connection with the wireless network.
• The utilization of the Wifipumpkin3 tool enables the execution of a phishing manoeuvre, wherein the user's login credentials are enticed through the presentation of an enticing user login and password interface when connecting to the specific wifi network. 
• The DarkLogin proxy facilitates the automatic presentation of the login page for users connecting to the network through a series of scripts.

Output: 


![Part - 4](https://github.com/Ibarsjoel1234/Sparrow-Wifi/assets/35426719/db2539bd-90e9-4807-a7b2-ab8918cc43a7)


