# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

### NAME : MOHAN RAJ C
### REG NO : 212223040114

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
<img width="750" height="617" alt="Screenshot 2025-09-21 122352" src="https://github.com/user-attachments/assets/e5f9abbb-a66a-434b-991d-bd88e5b533f7" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
<img width="1117" height="438" alt="image" src="https://github.com/user-attachments/assets/fabcaa1a-0802-45bf-bdab-189e37312405" />


 dsniff:


<img width="1034" height="371" alt="image" src="https://github.com/user-attachments/assets/d3a3465c-32c3-4dcf-9eca-08218e616c36" />




In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
<img width="701" height="730" alt="Screenshot 2025-09-21 123530" src="https://github.com/user-attachments/assets/e9d0231e-c044-4f29-9101-fab1fc9c1b8d" />





In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

Invoke the wireshark and examine the various menus  and controls of the tool:

<img width="1918" height="881" alt="image" src="https://github.com/user-attachments/assets/6cc98ba8-574f-4954-a9a6-c0501927b5f6" />

## Ettercap:
<img width="1667" height="879" alt="Screenshot 2025-09-21 124916" src="https://github.com/user-attachments/assets/664a0e80-0dec-4da3-bec1-24ab8ba9d5ba" />



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
