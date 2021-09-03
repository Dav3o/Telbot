!Version requires depricated!
# Telbot
Telbot is an advertising bot for Telegram based on the PyAutoGUI module, you can automate advertising in groups with this Project

## Requirements
For this script to work, you need to have python3 installed, the other requirements will be installed with the installation script 

## Installation
**1. Clone the repository**
```
git clone https://github.com/Dav3o/Telbot.git
```
**2. Install requirements**
```
chmod +x install.sh
sudo ./install.sh
```
## Usage
This script will recognize if Telegram-web is opened and you are logged in, it will start as soon you are logged in
```
python3 Telbot.py --help
```
![grafik](https://user-images.githubusercontent.com/61215846/120109041-033cae00-c168-11eb-9996-08b79a4f13da.png)

**Example**
```
python3 Telbot.py -f groups.txt -l https://www.youtube.com/watch?v=unUXGT0cmZQ -t 40 
```
This will post a youtube link in the groups, provided by the groups.txt file for 40 minutes 

**Clear Log file**
```
chmod +x clear.sh
sudo ./clear.sh
```
The Log file will be automatically cleared when you start a new session
