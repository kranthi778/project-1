# CEH project-1 - Linux and Network Reconnaissance


##  1. whoami

### command :
          whoami

### output :
         luffy5250
                                                                                                                                                                                                                                             
### Explanation :
         This displays the username of the currently logged-in user


## 2. id 

### command : 
          id 

### output : 
         uid=1000(luffy5250) gid=1000(luffy5250) groups=1000(luffy5250),4(adm),20(dialout),24(cdrom),25(floppy),27(sudo),29(audio),30(dip),44(video),46(plugdev),100(users),101(netdev),102(scanner),112(bluetooth),117(lpadmin),119(wireshark),123(vboxsf),124(kaboxer)


### Explanation : 
              This shows the User ID (UID),Group ID (GID), and group membership.


## 3. hostname 

### command :
       ```bash
       hostname
      ```
### output :
       ```text
       kali
      ```
### Explanation :
         Displays the name of the computer on the network.

## 4. hostctl

### command :
        ```bash 
        hostnamectl
          ```
### output : 
```text  
 Static hostname: kali
       Icon name: computer-vm
         Chassis: vm 💽
      Machine ID: edc1f06e1bb9409fb6a2d76f2ed63587
         Boot ID: 5448050857cf475c85006c89596d1073
  Virtualization: oracle
Operating System: Kali GNU/Linux Rolling   
          Kernel: Linux 6.19.14+kali-amd64
    Architecture: x86-64
 Hardware Vendor: innotek GmbH
  Hardware Model: VirtualBox
Hardware Version: 1.2
Firmware Version: VirtualBox
   Firmware Date: Fri 2006-12-01
    Firmware Age: 19y 6month 3w 4d 
  ```
### Explanation :
            Diapays detailed system and hostnames information
              shows the Hostname,operating system,kernel version and system architecture.




## 5. Kernel Information

### Command
```bash
uname -a
```

### Explanation :
      Displays detailed information about the Linux kernel and system architecture.

         
                                                                                                               
## 6. Operating System Details

### Command
```bash
cat /etc/os-release
```

### Explanation :
     Displays detailed information about the installed Linux distribution.

                                                                                                                                                                                                                                            


## Skills Learned
    Basic Linux commands
    User identification
    System identification
    Operating system information
    Kernel information
