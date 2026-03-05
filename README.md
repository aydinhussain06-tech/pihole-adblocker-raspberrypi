#  Host based ad blocker using a Raspberry Pi Zero 2 W.

This project shows the setup of my host based ad blocker using Raspberry Pi 2 Zero W

The Raspberry Pi blocks ads and malicious content at the SOHO network level using Pi hole

Reconfigured the DNS server to the Pi hole, allowing automatic DNS resolution, blocklisting ads and malicious domains, and allowing configuration on each device connected to the wifi.

<img width="2549" height="1518" alt="image" src="https://github.com/user-attachments/assets/658ec2e6-44e7-44ef-998c-6d06fa3546ee" />

# Tools used: 
- Micro SD Card
- Micro Adapter
- Rapsberry Pi Zero 2 W
- SD Card Reader
- Micro usb connecter
<img width="200" height=auto alt="image" src="https://github.com/user-attachments/assets/30a67ac6-d9dc-4625-a630-9f6e526203c7" />

# Initial Raspberry Pi Configuration
- Created username and password
- Enabled SSH
- Installed packages
- Connected micro SD card to raspberry pi
<img width="200" height=auto alt="image" src="https://github.com/user-attachments/assets/0ca0fc0e-ac0e-474c-8947-7e626cf67c61" />

# Installing pi hole and final setups
- Logged into raspberry pi through SSH
- Installed pi hole on it
- Logged into router and reserved the IP of the raspberry pi
<img width="200" height=auto alt="image" src="https://github.com/user-attachments/assets/ab4e7f45-4dad-4df8-8373-0fc828d09577" />

# Troubleshooting
- When manually changing my router's DNS server to the raspberry pi's static ip address it disconnects from having internet connection
- Bell (my IPS) restricts custom DNS at the router level

# Fix
- Manually configure the DNS server on each device by setting it to the IP of the raspberry PI
- Statically assigned IP for my TV since I set the IP settings to static
- Added extra blocklists for youtube ads
<img width="200" height=auto alt="image" src="https://github.com/user-attachments/assets/658ec2e6-44e7-44ef-998c-6d06fa3546ee" />
