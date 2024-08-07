### Kali Cheat-sheet ###

![image](https://user-images.githubusercontent.com/25408117/177054560-432167b0-a165-4918-af41-b177104e1576.png)

**Passwordless Root**  
sudo dpkg-reconfigure kali-grant-root

**GIT**  
```
sudo apt install git
```

**Create Bash Aliases File**  
```
sudo nano ~/.bash_aliases
```

**Example Alias**  
```
alias update='sudo apt-get update'
```
*Ctrl+X, Y then Enter to save.*

**Updater function**  
```
function apt-updater {  
		apt-get update &&  
		apt-get dist-upgrade -Vy &&  
		apt-get autoremove -y &&  
		apt-get autoclean &&  
		apt-get clean &&  
		reboot  
		}
```

**Install Tilix**  
```
Sudo apt install tilix
```

**Run Tilix**  
```
Tilix
```

**Figlet ASCII Fonts**  
```
sudo apt-get install figlet
```

**jp2a ASCII Picture converter PNG > JPG ASCII**  
```
sudo apt-get install jp2a
```

**#Add the Tor Project repositories to your APT repository list.**  
```
echo 'deb https://deb.torproject.org/torproject.org stretch main
deb-src https://deb.torproject.org/torproject.org stretch main' > /etc/apt/sources.list.d/tor.list
```
