# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
From kali linux issue the command : sudo arpspoof -i eth0 -t
![image](https://github.com/Naadira/ARP-Attack-and-Network-Sniffing/assets/128135126/bb8d0f94-1b41-4dd3-bc56-30a3eb2067e8)

From Kali linux issue the command : sudo arpspoof -i etho -t
![image](https://github.com/Naadira/ARP-Attack-and-Network-Sniffing/assets/128135126/68f1a3c1-f3f1-4452-84bf-b2e80785bbcf)

 dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
 ## OUTPUT:
![image](https://github.com/Naadira/ARP-Attack-and-Network-Sniffing/assets/128135126/972e06a2-1f95-4998-8a64-f30d0c06c683)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/Naadira/ARP-Attack-and-Network-Sniffing/assets/128135126/aa8b0321-5e0b-4c74-88d2-be317f8ed0d6)

Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/Naadira/ARP-Attack-and-Network-Sniffing/assets/128135126/cf1722d1-2923-4ea6-91be-c04ca79ea3e2)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
