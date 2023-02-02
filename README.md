# Connect_to_ubuntu_through_ssh
how do I connect to my VM ubuntu though ssh

1. Open the terminal of my ubuntu VM
2. Install openssh
```Bash
sudo apt-get install openssh-server
```
3. Enable the ssh service by typing :
```Bash
sudo systemctl start ssh
## OR enable and start the ssh service immediately ##
sudo systemctl enable ssh --now
```
4. Look for your IP addres : (Ex: 192.168.x.y)
```Bash
ifconfig
```
5. Open WSL
6. On my Host connect to the vm :
```Bash
ssh userName@Your-server-name-IP
```
