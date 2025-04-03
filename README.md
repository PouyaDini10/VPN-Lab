# 🌐 VPN-Lab
<img width="590" alt="image" src="https://github.com/user-attachments/assets/a10adeeb-c38a-4807-b305-3c9595255aef" />

## 🧰 Tools used 
- Azure
- My personal machine
- ProtonVPN
- "whatismyipaddress.com"

## 🧠 Objective
The goal of this lab is to analyze change in Public IP Address through my personal computer, an Azure virtual machine, that same virtual machine connected to a VPN(Virtual Private Network). 

## 📍 Understanding IP addresses & VPN's

What is an IP(Internet Protocol) address? 

You can think of **IP(Internet Protocol)** addresses as your home address, every device is assigned a unique identifier that's used to send and receive data. IP addresses come in two forms:

**Public IPs** - visible on the internet

**Private IPs** - used within your own internal network

<br>

**IPv4 -** Internet Protocol version 4 

Most common version of IP addresses used today
192.168.1.1(an example)

**IPv6 -** Internet Protocol version 6

A newer version, created because were in shortage of IPv4 addresses
2001:0db8:85a3:0000:0000:8a2e:0370:7334(an example)

**Static IP addresses -** fixed

**Dynamic IP addresses -** the IP address changes over time(usually through ISP or DHCP)

<br>

**VPN(Virtual Private Network)**

What is a VPN? 

A VPN creates a secured, encrypted network tunnel between your device and the internet. Essentially, it hides your IP by routing traffic through a VPN server in another country. 

## Identifying My Local IP Address

- visit "whatismyipaddress.com"
- document all the key details

<img width="310" alt="image" src="https://github.com/user-attachments/assets/d35fe868-f47e-4b6e-8eac-5d3710e1c5eb" />

## Setting up & Identifying VM's IP address
- Create a resource group
- Create a Windows 11 virtual machine
- Inside the Windows 11 VM, download Proton VPN.
- Browse to “whatismyipaddress.com”, take note of the details.

![image](https://github.com/user-attachments/assets/915d6588-f9c7-4eb0-a1b6-35c60c9d2980)

## ProtonVPN

Within you Windows 11 VM:

- Setup your ProtonVPN server to another country
- Back in "whatismyipaddress.com", take note of the details
- Exmamine regular google searches



  



























