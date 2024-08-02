## Use Command

- `sudo passwd` <username>  to change user password
 `sudo usermod` -u 1004 (id) <username> to change user id
 `sudo userdel -r`  <username> to delete user
 ` sudo mkdir /home/ ` <username> to make user directory on the home directory
` sudo - <username>`  to change user on terminal
` sudo usermod <username> -s  /bin/bash`  to change terminal type


`sudo visudo`  to change user to sudoer

`etc/shadow`  where password place

`ls -l`  to display content 

### Permission (rwx)
 sudo chmod <username> <filename>  change owner of file
 sudo chmod <username>:<groupname> to change owner and group name

sudo +x <filename>  to change permission of file 

sudo chmod +s <filename> to change permission on execute

### Package Installation on Linux

sudo apt update to update system
sudo apt search <software name>  to search software
sudo apt install <software name> to install software
sudo apt remove <software name> to remove software not dependence
sudo apt upgrade <software name> to  search and install if available
sudo apt purge <software name> to remove software and dependence




