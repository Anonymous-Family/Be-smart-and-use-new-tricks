
###### <p align="center"> GPS Location Tracker (Android, IOS, Windows phones.)

###### <p align="center">*This is official repository maintained by us*
###### <p align="center"> *You can check [youtube](https://www.youtube.com/channel/UCEwbeJ7NS5s4GjfSMm9NFLA)🔐*

## emperor X 🔐🗝️🔓

Concept behind scorpion.py is simple, just like we host phishing pages to get credentials why not host a fake page that requests your location like many popular location based websites. Read more on Seefu AL-janabi Blog eyescorpion.py Hosts a fake website which asks for Location Permission and if the target allows it, we can get :

* Longitude
* Latitude
* Accuracy
* Altitude - Not always available
* Direction - Only available if user is moving
* Speed - Only available if user is moving

Along with Location Information we also get **Device Information** without any permissions :

* Unique ID using Canvas Fingerprinting
* Device Model - Not always available
* Operating System
* Platform
* Number of CPU Cores - Approximate Results
* Amount of RAM - Approximate Results
* Screen Resolution
* GPU information
* Browser Name and Version
* Public IP Address
* Local IP Address
* Local Port


Available Templates :

* WhatsApp group
* Telegram
* Sex +18 (;

## Tested On :

* Kali Linux
* BlackArch Linux
* Ubuntu
* Kali Nethunter
* Termux
* Parrot OS

## Installation

### Basic For Beginners

```bash
$ git clone https://github.com/Anonymous-Family/Be-smart-and-use-new-tricks.git
$ cd EyeScorpion
$ python3 EyeScorpion.py -t manual -k testkml
```

### ngrok setup

```bash
go to ngrok.com (Login)
Download ngrok
$ unzip ngrok.zip
$ ./ngrok authtoken *******
$ ./ngrok http 122
send link to victim
```

### Kali Linux / Ubuntu / Parrot OS

```bash
git clone https://github.com/Anonymous-Family/Be-smart-and-use-new-tricks.git
cd EyeScorpion
apt update
apt install python3 python3-pip php
pip3 install requests
```

### BlackArch Linux

```bash
pacman -S eyescorpion.py
```

### Termux

```bash
git clone https://github.com/Anonymous-Family/Be-smart-and-use-new-tricks.git
cd EyeScorpion
pkg update
pkg install python php
pip3 install requests
```

## Usage

```bash
python3 eyescorpion.py -h

usage: eyescorpion.py [-h] [-s SUBDOMAIN]

optional arguments:
  -h, --help            show this help message and exit
  -k KML, --kml         Provide KML Filename ( Optional )
  -p PORT, --port       Port for Web Server [ Default : 122 ]
  -t TUNNEL, --tunnel   Specify Tunnel Mode [ Available : manual ]

##################
# Usage Examples #
##################

# Step 1 : In first terminal
$ python3 eyescorpion.py -t manual

# Step 2 : In second terminal start a tunnel service such as ngrok
$ ./ngrok http 122

###########
# Options #
###########

# Ouput KML File for Google Earth
$ python3 eyescorpion.py -t manual -k <filename>

# Use Custom Port
$ python3 eyescorpion.py -t manual -p 1337
$ ./ngrok http 1337

```

### Legal Disclaimer :

Usage of the tool for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program

-------------------------------------------------------------------------------------
## Follow on:
<p align="left">
<a href="https://github.com/Anonymous-Family"><img src="https://img.shields.io/badge/GitHub-Follow%20on%20GitHub-inactive.svg?logo=github"></a>
</p><p align="left">
<a href="https://www.facebook.com/kali14562/"><img src="https://img.shields.io/badge/Facebook-Follow%20on%20Facebook-blue.svg?logo=facebook"></a>
</p><p align="left">
<a href="https://t.me/+cfFn8OTSF65jZDM0"><img src="https://img.shields.io/badge/Telegram-Contact%20Telegram%20Profile-blue.svg?logo=telegram"></a>
</p><p align="left"> 

-------------------------------------------------------------------------------------
