# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

# STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

# ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
# OUTPUT:
![VirtualBox_windows7_05_10_2023_08_57_33](https://github.com/KRISHNARAJ-D/ARP-Attack-and-Network-Sniffing/assets/119559695/c48bf826-feef-408b-9927-f98c400f114c)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
# OUTPUT:
![241191984-a70b28b6-7f35-43b5-92d7-840f43f1bf82](https://github.com/KRISHNARAJ-D/ARP-Attack-and-Network-Sniffing/assets/119559695/9ecb9342-90f8-43cb-afe4-890c3afe02b8)


 # dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
# OUTPUT:

![241192115-e985ae01-13fa-42f1-8155-94b04deddecb](https://github.com/KRISHNARAJ-D/ARP-Attack-and-Network-Sniffing/assets/119559695/368f1db8-04ba-4087-a618-82a2cba8c543)



In Kali issue the following commands:sudo dsnifff
# OUTPUT:

![241192308-b683d8ad-117e-44c7-b03c-bdd0b0f7e4c0](https://github.com/KRISHNARAJ-D/ARP-Attack-and-Network-Sniffing/assets/119559695/6f7ac088-b8ee-47b7-8cf2-6d2daa43498e)


# Invoke the wireshark and examine the various menus  and controls of the tool:

![241192334-e9461986-63fa-4577-8c66-ccb63a3c56bf](https://github.com/KRISHNARAJ-D/ARP-Attack-and-Network-Sniffing/assets/119559695/5e33c6f8-bef2-4b76-8031-98eab54004ee)


# RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
