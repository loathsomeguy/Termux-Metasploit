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
pkg install postgresql
pkg install openssh wget curl git -y
wget https://raw.githubusercontent.com/loathsomeguy/metasploit/main/metasploit.sh
chmod +x metasploit.sh
./metasploit.sh
```
## After installation complete
Start `postgresql`
```bash
./postgresql_ctl.sh start
```
And run `msfconsole`
```bash
msfconsole
```

## How it is useful?

* It is used to retrieve all the messages, contacts, call-logs from the Target Mobile on the same or different Network. However you need to learn how to do port-forwarding in order to do it on different network.

## Warning
***This tool is only for educational purpose. If you use this tool for other purposes except education we will not be responsible in such cases.***
