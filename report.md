# VPN Report — Task 7

**Author:** Likhith Bharadwaj Reddy  
**Date:** 03-10-2025  

---

## 1. Introduction
The purpose of this task was to gain practical experience with VPNs and understand how they help in maintaining online privacy. I chose ProtonVPN (free tier) for this task because it provides a secure client, supports multiple platforms, and offers free servers for testing.

---

## 2. Methodology
- Signed up for a free ProtonVPN account.  
- Downloaded and installed the ProtonVPN Windows client.  
- Logged in with my credentials and connected to the “Fastest Server” option.  
- Verified IP address before and after connection using:  
  - `curl ifconfig.me` (command line)  
  - [whatismyipaddress.com](https://whatismyipaddress.com) (browser)  
- Browsed a few websites to confirm VPN encryption worked.  
- Disconnected VPN and checked my original IP was restored.  

---

## 3. Results / Observations
| Scenario            | IP Address Observed (example)   | Notes |
|---------------------|---------------------------------|-------|
| Before VPN (OFF)    | 49.xxx.xxx.xxx (India ISP)      | Real ISP IP |
| After VPN (ON)      | 185.xxx.xxx.xxx (Proton server) | Masked IP |
| Browsing Speed      | Slightly slower than normal     | Normal effect |
| Connection Stability| Stable throughout session       | No drops |

---

## 4. Discussion
- The VPN successfully masked my real IP and replaced it with the ProtonVPN server IP.  
- There was a noticeable but minor drop in speed, which is expected due to encryption overhead.  
- Browsing remained stable and websites loaded without issues.  
- Disconnecting the VPN immediately restored my original IP address.  
- This confirmed that VPN tunneling and encryption were working properly.  

---

## 5. Conclusion
This task helped me understand how VPNs function in practice. I was able to successfully install, connect, and verify IP masking with ProtonVPN. I also observed the expected speed trade-offs and confirmed that VPNs provide privacy benefits but not complete anonymity.

---

## 6. References
- ProtonVPN Documentation: https://protonvpn.com/support  
- What Is My IP: https://whatismyipaddress.com  
- WireGuard Protocol: https://www.wireguard.com  
