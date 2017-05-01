Instruction<br>
<br>
Connecting to AWS:
<br>
1. Disconnect from your company VPN <br>
2. Create Private key using PuttyGen tool<br>
3. Connect to AWS node using putty adding the private key <br>
<br>
System Configuration Checks<br>
1. Setting Swappiness to 1<br>
sudo su<br>
echo 1 > /proc/sys/vm/swappiness<br>
<br>
2. Show the mount attributes of your volume(s)<br>
3. If you have ext-based volumes, list the reserve space setting XFS volumes do not support reserve space<br>
4. Disable transparent hugepage support<br>
5. List your network interface configuration<br>
6. Show correct forward and reverse host lookups<br>
   For /etc/hosts, use getentFor DNS, use nslookup<br>
7. Show the nscd service is running<br>
8. Show the ntpd service is running<br>
