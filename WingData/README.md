# WingData - HackTheBox Writeup

- **Target:** Wingdata.htb
- **Result:** Pwned (User & Root)

## Summary
1. **Enumeration:** Port 80 (WingFTP) discovered.
2. **Initial Access:** Exploited WingFTP RCE (Exploit-DB 52347). Gained user shell via custom bash payload.
3. **Privilege Escalation:** Exploited sudo privileges on a Python backup script to escalate to root.

## Flag Locations
- user.txt: /home/wacky/user.txt
- root.txt: /root/root.txt
