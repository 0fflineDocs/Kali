 _  __     _ _   _     _
| |/ /__ _| (_) | |   (_)_ __  _   ___  __
| ' // _` | | | | |   | | '_ \| | | \ \/ /
| . \ (_| | | | | |___| | | | | |_| |>  <
|_|\_\__,_|_|_| |_____|_|_| |_|\__,_/_/\_\

#Passwordless Root 
sudo dpkg-reconfigure kali-grant-root

#GIT
sudo apt install git

#Create Bash Aliases File
sudo nano ~/.bash_aliases

#Example Alias
alias update='sudo apt-get update'

#Ctrl+X, Y then Enter to save.

#Updater function
function apt-updater {
	apt-get update &&
	apt-get dist-upgrade -Vy &&
	apt-get autoremove -y &&
	apt-get autoclean &&
	apt-get clean &&
	reboot
	}

#Install Tilix
Sudo apt install tilix

#Run Tilix
Tilix

#Figlet ASCII Fonts
sudo apt-get install figlet

#jp2a ASCII Picture converter PNG > JPG ASCII
sudo apt-get install jp2a

#Add the Tor Project repositories to your APT repository list.
echo 'deb https://deb.torproject.org/torproject.org stretch main
deb-src https://deb.torproject.org/torproject.org stretch main' > /etc/apt/sources.list.d/tor.list
