# Sparrow Wifi 

## Deauth using Sparrow-Wifi and MITM using Wifiphisher and Airgeddon

## Description

## DDOS Attack

•	To commence, the initial step involved installing and upgrading Kali Linux through the terminal. Additionally, the sparrow wifi graphical user interface (GUI) tools are implemented to evaluate potential wifi service set identifiers (SSID). 
• This analysis is conducted to identify the target SSID, which is necessary for executing the assault. Furthermore, Sparrow WiFi conducts an analysis of the wireless local area network (WLAN), enabling monitoring and network discovery.  
• In addition to the steps, the user should proceed by choosing the target SSID and subsequently selecting the options for Deauthentication (single) and Deauthentication (continuous). 
• These options effectively result in the expulsion of clients from the wireless network, hence facilitating the successful execution of the Deauthentication Denial-of-Service (DoS) attack.

Deauthentication Broadcast - Single:

![image](https://github.com/Ibarsjoel1234/Sparrow-Wifi/assets/35426719/417a2ea3-c78a-4535-8d04-a63404842b70)

Deauthentication Broadcast - Continuous:

![image](https://github.com/Ibarsjoel1234/Sparrow-Wifi/assets/35426719/00af2060-1a26-4e77-870e-90b9554e38a7)

## Evil Twin Attack - Wifiphiser

• Wifiphisher tools have been used to analyze the possible SSID and select the target SSID. • Next, update the firmware upgrade option and start the attack. When the user tries to connect to the possible wifi (which is unencrypted), it will automatically pop up a notification called Firmware Upgrade with terms and conditions. 
• When the user submits the request, it will capture the user username and password, which will display on the terminal. 

Output:


![image](https://github.com/Ibarsjoel1234/Sparrow-Wifi/assets/35426719/cf91150b-5c59-4fbf-88fe-cebc65322f55)


## Evil Twin Attack using WifiPumpkin3 - GUI Format


• Software known as wifipumpkin3 possesses the capability to execute the Deauth Denial-of-Service (DoS) assault. 
• This process encompasses several steps, beginning with the installation of the WiFi Pumpkin program. 
• Subsequently, the Deauth interface is activated, and the BSSID, obtained through scanning, is referenced. 
• Finally, the attack is initiated by executing the START command. This has the potential to render the client device incapable of establishing a connection with the wireless network.
• The utilization of the Wifipumpkin3 tool enables the execution of a phishing manoeuvre, wherein the user's login credentials are enticed through the presentation of an enticing user login and password interface when connecting to the specific wifi network. 
• The DarkLogin proxy facilitates the automatic presentation of the login page for users connecting to the network through a series of scripts.

Output: 

![image](https://github.com/Ibarsjoel1234/Sparrow-Wifi/assets/35426719/97f38e0c-6897-40e4-a4bb-6ccc4a577a72)




