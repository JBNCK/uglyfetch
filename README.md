## Notice: As of August 2024 this Project is no longer under active development. More information can be found [here (german)](https://de.biernacik.org/meldungen/einstellung-projekte/).

# uglyfetch
I made this in line 30 minutes so don't expect anything good.

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
