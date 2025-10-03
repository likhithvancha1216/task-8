# Task 7 — Working with VPN’s

**Author:** Likhith Bharadwaj Reddy  
**Date:** 03-10-2025  

---

## Objective
The goal of this task was to understand how VPNs (Virtual Private Networks) work, configure one on my system, and verify how it changes my IP address and protects privacy.  

---

## Steps Performed
1. Chose **ProtonVPN Free Tier** as the VPN provider.  
2. Created an account on the ProtonVPN website.  
3. Downloaded and installed the ProtonVPN client for Windows.  
4. Logged in with my credentials and connected to the **Fastest Server** option.  
5. Verified my IP before and after connection using:  
   - `curl ifconfig.me` in the terminal  
   - [https://whatismyipaddress.com](https://whatismyipaddress.com) in the browser  
6. Browsed a few websites to confirm traffic was encrypted and working normally.  
7. Disconnected the VPN and checked that my IP reverted back to my original ISP address.  

---

## Observations
- When connected, my public IP changed from my ISP address in India to a ProtonVPN server address in another location.  
- Browsing speed was slightly reduced, which is expected due to encryption and rerouting.  
- Websites loaded normally, and HTTPS traffic worked without issues.  
- Disconnecting restored my original IP and faster speeds.  

---

## Key Learnings
- A VPN hides the real IP and adds a layer of encryption.  
- It helps in securing browsing on public Wi-Fi and bypassing geo-restrictions.  
- VPN cannot provide *complete* anonymity because the VPN provider can still log traffic if they choose.  
- Speed reduction is one of the main trade-offs when using VPNs.  

---

## Files in This Repository
- `commands.md` → Exact commands/steps followed  
- `report.md` → Detailed report with answers to interview questions  
- `.gitignore` → Ignored system files  

---

## Conclusion
This task helped me gain hands-on experience with VPNs. I was able to successfully set up ProtonVPN, verify my IP changes, and understand the benefits and limitations of using a VPN for privacy and security.
