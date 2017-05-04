Cloud Provider: AWS<br>
<br>
IP Addresses<br>
54.206.112.138<br>
54.206.37.242<br>
54.206.124.58<br>
54.252.131.188<br>
54.206.113.245<br>
<br>
<br>
<br>
List the Linux release you are using<br>
Centos 7.x<br>
<br>
<br>

[root@ip-172-31-14-184 centos]# su parted -lsu: user parted does not exist[root@ip-172-31-14-184 centos]# sudo parted -lModel: Xen Virtual Block Device (xvd)Disk /dev/xvda: 32.2GBSector size (logical/physical): 512B/512BPartition Table: msdosDisk Flags:
Number  Start   End     Size    Type     File system  Flags 1      1049kB  32.2GB  32.2GB  primary  xfs          boot
<br><br>
[root@ip-172-31-5-57 centos]# sudo parted -lModel: Xen Virtual Block Device (xvd)Disk /dev/xvda: 32.2GBSector size (logical/physical): 512B/512BPartition Table: msdosDisk Flags:
Number  Start   End     Size    Type     File system  Flags 1      1049kB  32.2GB  32.2GB  primary  xfs          boot  
<br><br>
[centos@ip-172-31-11-177 ~]$ sudo parted -l Model: Xen Virtual Block Device (xvd) Disk /dev/xvda: 32.2GB Sector size (logical/physical): 512B/512B Partition Table: msdos Disk Flags:  Number  Start   End     Size    Type     File system  Flags  1      1049kB  32.2GB  32.2GB  primary  xfs          boot
<br><br>
[centos@ip-172-31-6-2 ~]$ sudo parted -lModel: Xen Virtual Block Device (xvd)Disk /dev/xvda: 32.2GBSector size (logical/physical): 512B/512BPartition Table: msdosDisk Flags:
Number  Start   End     Size    Type     File system  Flags 1      1049kB  32.2GB  32.2GB  primary  xfs          boot
<br><br>
[centos@ip-172-31-10-171 ~]$ sudo parted -lModel: Xen Virtual Block Device (xvd)Disk /dev/xvda: 32.2GBSector size (logical/physical): 512B/512BPartition Table: msdosDisk Flags:
Number  Start   End     Size    Type     File system  Flags 1      1049kB  32.2GB  32.2GB  primary  xfs          boot
<br>
<br>
[root@ip-172-31-14-184 centos]# yum repolist enabledLoaded plugins: fastestmirrorLoading mirror speeds from cached hostfile * base: mirror.nsw.coloau.com.au * extras: mirror.nsw.coloau.com.au * updates: mirror.nsw.coloau.com.aurepo id                             repo name                             statusbase/7/x86_64                       CentOS-7 - Base                       9,363extras/7/x86_64                     CentOS-7 - Extras                       337updates/7/x86_64                    CentOS-7 - Updates                    1,577repolist: 11,277

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>


