# Linux Network Services Deployment (Ubuntu & VirtualBox)

This project demonstrates the setup and configuration of important network services on **Ubuntu Linux** using **Oracle VirtualBox**. The system simulates a small enterprise network with server and client machines.

## 🚀 Features

* Virtual network setup using VirtualBox.
* Internet access using NAT Adapter.
* Secure internal communication using Host-Only Adapter.
* FTP server configuration for file sharing.
* Apache web server setup for hosting web pages.
* DNS server configuration for domain name resolution.
* DHCP server setup for automatic IP address assignment.

---

# 🛠️ Services Configured

## 1. FTP Server

* Software: `vsftpd`
* Used for file transfer between systems.

## 2. Web Server

* Software: Apache2
* Hosts web pages accessible within the local network.

## 3. DNS Server

* Software: `bind9`
* Converts domain names into IP addresses.

## 4. DHCP Server

* Software: `isc-dhcp-server`
* Automatically assigns IP addresses to clients.

---

# 🌐 Network Setup

## Adapter 1: NAT

* Provides internet access for updates and installations.

## Adapter 2: Host-Only Adapter

* Creates a private local network between virtual machines.

---

# 🛠️ Technologies Used

* Ubuntu Linux
* Oracle VirtualBox
* Apache2
* vsftpd
* bind9
* isc-dhcp-server

---

# ▶️ Project Purpose

This project helps in understanding Linux server configuration, networking concepts, and deployment of common network services in a virtual environment.
