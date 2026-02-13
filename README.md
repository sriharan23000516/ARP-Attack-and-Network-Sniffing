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
<img width="770" height="714" alt="image" src="https://github.com/user-attachments/assets/b5dafd78-cd79-47d0-aa9c-dbe584c8970a" />


## From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
<img width="679" height="594" alt="image" src="https://github.com/user-attachments/assets/2c43d23c-28f7-4fa9-8a66-186b730e1015" />


 
 ## dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

<img width="699" height="673" alt="image" src="https://github.com/user-attachments/assets/27dd10f1-5dbe-4b4e-b6be-e15e4ffdf45d" />



## WIRESHARK :

## OUTPUT:
<img width="939" height="654" alt="image" src="https://github.com/user-attachments/assets/ad5cc8a5-335a-49e2-a1de-74785803656f" />

Invoke the wireshark and examine the various menus  and controls of the tool:

## ETTERCAP :
ettercap supports active and passive dissection of many protocols and includes many features for network and host analysis.

<img width="926" height="546" alt="image" src="https://github.com/user-attachments/assets/69fcac2d-9ba7-48cd-81d4-6b9931c1128d" />


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
