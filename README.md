# uglyfetch
Fetcher for Linux. I made it in line 30 minutes so don't expect anything.

![](demos/uglyfetch_demo.jpg)
# Requirements
- Figlet
- Lolcat
- Git
- Inetutils
- Pciutils
# Installation
Install all of the requirenments first (package names may vary by distro). Next, clone the repository and install like this:
```
git clone https://github.com/JBGMR/uglyfetch.git && cd uglyfetch && sh install.sh
```
If you are on Arch run the following line to install all the requirements and the progran itself:
```
sudo pacman -S git figlet lolcat inetutils pciutils && git clone https://github.com/JBGMR/uglyfetch.git && cd uglyfetch && makepkg -si
```
To run the program type ``uglyfetch``
# Removing
Execute the following:
```
sudo rm /bin/uglyfetch
```
