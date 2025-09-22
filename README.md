# Basic-Nmap-Scan
This is the a basic nmap scan to get to know the basic scanning 

**Installation**

sudo apt install nmap -y


We will be scanning our own network for demonstration purpose.
To find our IP address we use the command **ifconfig**  and look for the ipv4 address at eth0

Use the IP to perform the nmap scan.

**Command**:nmap {ip} -sS

If you dont have any open ports or services running there wont be much to see in the output

