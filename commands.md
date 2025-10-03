# Task 7 — Working with VPN’s

**Author:** Likhith Bharadwaj Reddy  
**Date:** 03-10-2025  

---

## Objective
To set up a VPN (ProtonVPN free tier), connect to a server, verify the IP change, test browsing, and understand the effect on privacy and speed.  

---

## Steps and Commands

### 1. Install VPN Client

  Download and install from https://protonvpn.com/download  

### 2. Login and Authenticate
  protonvpn login your_email@example.com

### 3. Connect to VPN
- Connect to fastest available server:
  protonvpn c --fastest
- Connect to a specific country (example: US):
  protonvpn c US

### 4. Verify IP address
#### Before connecting
- curl ifconfig.me
- curl ipinfo.io/ip  
#### After connecting
- curl ifconfig.me
- curl ipinfo.io/ip


### 5.Disconnect VPN
- protonvpn d

### 6. Optional Speed Test
- ping google.com
  speedtest-cli




