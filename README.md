# <img src="https://github.com/user-attachments/assets/a7e6c7ef-ce86-414b-a651-f1f35c61235a" width="200"/> <br> Unprotected Cyber<br><img src="https://img.shields.io/github/v/release/hopeaxolotl/unprotected-cyber?style=for-the-badge"> <br> <img src="https://img.shields.io/badge/DISTRIBUTION-UBUNTU%2020/22,%20DEBIAN%2036-green?style=for-the-badge"><br>
Unprotected Cyber is a system hardening script built primarily for the securing of CyberCenturion/Patriot competition scenarios. It is now primarily used as a tool to quickly configure and edit certain Linux scripts.  <br> [Link to website here](https://youtube.com/@hopemapping)
<br>
<br>
Unprotected Cyber is primarily made in Python, along with a compilation of Bash files, who's primary purpose is to configure files to be as secure as possible. It is also possible to mod, using the bash files provided in the /unproc/opts, /unproc/misc, /unproc/service and /unproc/man folders. 
<br>
<br>
The legacy version of the script of which this script is based on the I am Root CyberCenturion Script and the Gl0ckrain CyberCenturion Script.
<br>
<br>
# Screenshots
## tbc
# How to Use
## Getting Started
1 - Download .deb file from GitHub repository. <br>2 - Run: `sudo apt install -y ./path/to/deb/unprotectedcyber.deb`.<br>3 - When installed, run `python3 /unproc/unprotectedcyber.py` to start script.
## General Usage
 - Automatic scripts are blocks of individual scripts (manual scripts) bunched together for convenience.
 - Each individual manual script contains a unit of code dedicated to a single configuration/purpose, for example, "Malware and Updates".
## Misc/Services/Optional Usage
 - Miscellaneous scripts are made of miscellaneous scripts and lines of code that don't fit into any one category.
 - Services scripts are made of a single script used to configure a Linux service, for example SSH.
 - Optional scripts are scripts that aren't really needed for a secure system but added for convenience, for example the "Autoremove" option.
## Mod Guide (Unofficial)
 - All source bash files are located within folder ./unproc/.
 - From there, most moddable files are within each folder, like /opts/ and /services/.
## Dependencies
 - Dependencies should be automatically installed when you install via .deb, but just in case, the dependencies are:
# Known Issues
 - Can't run the script as the root user. Alternatively, run as a sudoer and run `sudo python3 /unproc/unprotectedcyber.py`.
 - Some users have to run `cd /unproc/` to get it running.
```
sudo apt install -y python3
sudo apt install -y python3-pip
sudo apt install -y python3-pyqt5
```
# Credits
## Primary Developers:
 - [HopeAxolotl](https://github.com/hopeaxolotl)
 - [Kezznator](https://github.com/kerron123456)
 - [Sienna7002](https://github.com/sienna7002)
## Moral Support:
 - [MintImperial](https://github.com/addmewim)
## Special Thanks:
 - Developers of I am Root CyberCenturion script.
 - Developers of Gl0ckrain CyberCenturion script.
