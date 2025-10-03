# Task 8 — Working with VPNs

**Author:** Likhith Bharadwaj Reddy  
**Date:** 03-10-2025  

## Objective  
The goal of this task was to understand how VPNs (Virtual Private Networks) work, configure one on my system, and verify how it changes my IP address and helps with privacy.

---

## Steps Performed  
1. Chose **ProtonVPN Free Tier** as the VPN provider.  
2. Created an account on ProtonVPN.  
3. Installed the ProtonVPN client on Windows.  
4. Logged in and connected to the “Fastest Server” option.  
5. Verified IP before and after using commands / websites:  
   - `curl ifconfig.me`  
   - `https://whatismyipaddress.com`  
6. Browsed websites to ensure traffic was encrypted and functional.  
7. Disconnected VPN and confirmed the IP reverted to the original.

---

## Observations & Learnings  

- When connected, my public IP changed from my ISP’s address to a ProtonVPN server address.  
- Browsing speed was slightly slower (expected, due to encryption overhead).  
- Websites continued to load normally (HTTPS traffic worked).  
- Disconnecting restored original IP and faster speed.  
- **Key Learnings**:  
  - VPN hides real IP and adds encryption  
  - Useful for secure browsing, bypassing geo-restrictions  
  - Doesn’t guarantee complete anonymity  
  - Tradeoff: reduced speed  

---


## Files & Structure

- `commands.md` — Exact commands / steps followed  
- `report.md` — Detailed report, analysis, answers  
- `Screenshots/` — Folder containing all screenshot images  
---

## Conclusion  
This task gave me hands-on experience installing and using a VPN, observing how IPs change, and understanding tradeoffs like speed, privacy, and limitations.

