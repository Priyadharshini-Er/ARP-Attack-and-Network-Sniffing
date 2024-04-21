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
![wind](https://github.com/Priyadharshini-Er/ARP-Attack-and-Network-Sniffing/assets/119558093/e61fb674-c7c6-48c6-be1e-321f448a8d9b)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![kali 1](https://github.com/Priyadharshini-Er/ARP-Attack-and-Network-Sniffing/assets/119558093/6a8b7aa8-1a8d-42bd-aa8f-d2ec75d1b72d)



 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![meta](https://github.com/Priyadharshini-Er/ARP-Attack-and-Network-Sniffing/assets/119558093/100245bd-b672-4e52-a8b7-8e294aecf8e0)





In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![kali out](https://github.com/Priyadharshini-Er/ARP-Attack-and-Network-Sniffing/assets/119558093/6072232d-8f51-4d03-943a-b66a5147e06f)



Invoke the wireshark and examine the various menus  and controls of the tool:
![wire](https://github.com/Priyadharshini-Er/ARP-Attack-and-Network-Sniffing/assets/119558093/790b13dc-f81e-4cf9-98bc-cef15e6b2fdc)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
