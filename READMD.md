

obianuju onyinye
 
From:
obiasedos@yahoo.com
To:
obianuju onyinye

Wed, 11 Dec at 12:13

Linux administration comprised of Applications and Storage

what is Applications

What is Storage 





TO ADD USER TO THE SUDOER FILE in ubuntu/debian

visudo

nice ALL=(ALL:ALL) ALL

OR 

sudo adduser nice

sudo passwd nice



TO ADD USER TO THE SUDOER FILE in ubuntu/debian

sudo usermod -aG sudo <username>

groups nice      ......to verify user is added in the group

su - nice





TO ADD USER TO THE SUDOER FILE in centos/fedora

sudo usermod -aG wheel <username>

groups nice      ......to verify user is added in the group

su - nice

sudo whoami





SSH CONNECTION FROM SERVER TO SERVER WITH SSH-KEYGEN COMMAND 

ssh-keygen

ssh-copy-id username@ip-address of remote server

ssh username@ip-address of remote server





ENABLE FIREWALL ON REMOTE SERVER

sudo ufw status



ENABLE PORTS ON REMOTE SERVER

sudo apt install ssh

sudo systemctl status sshd         .....If not active use the next command

sudo systemctl restart sshd



install or disbale firewall 

sudo apt install ufw

sudo ufw disable 

sudo ufw allow OpenSSH

sudo ufw allow 22/tcp  80/tcp   or 443//tcp        ....... opens a specific port

sudo ufw deny22/tcp   OR  80/tcp    or 443//tcp        ....... denies s a specific port



apt systemctl status sshd 



INSTAAALATIONS AND PACKAGE MANAGERS 

3. Install curl on your remote server

sudo apt update && sudo apt upgrade

sudo apt-get install curl

curl --version



4. 











