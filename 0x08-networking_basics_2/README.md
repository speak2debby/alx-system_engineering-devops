# 0x08. Networking basics #1

## Description
This project covers:

- [localhost/127.0.0.1](https://en.wikipedia.org/wiki/Localhost)
- [What 0.0.0.0 is](https://en.wikipedia.org/wiki/0.0.0.0)
- [Host file ```/etc/hosts```](https://www.makeuseof.com/tag/modify-manage-hosts-file-linux/)
- [How to display your machine’s active network interfaces ```Netcat```](https://www.thegeekstuff.com/2012/04/nc-command-examples/)

## Table of contents
Files | Description
----- | -----------
[0-change_your_home_IP](./0-change_your_home_IP) | Bash script that configures an Ubuntu server with the below requirements. ```localhost``` resolves to ```127.0.0.2``` ```facebook.com``` resolves to ```8.8.8.8```
[1-show_attached_IPs](./1-show_attached_IPs) | Bash script that displays all active IPv4 IPs on the machine it’s executed on.
[100-port_listening_on_localhost](./100-port_listening_on_localhost) | Bash script that listens on port ```98``` on ```localhost```
