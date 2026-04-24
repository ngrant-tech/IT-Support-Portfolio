# Cannot Access Company Website

## Summary
User unable to access internal company website.

## User
Daniel Foster

## Department
Marketing

## Issue
User reports that the internal company website does not load, while external websites function normally.

---

## Troubleshooting
- Reproduced issue by accessing internal website
- Verified external connectivity (Google reachable)
- Checked network configuration using ipconfig /all
- Identified incorrect DNS server assignment
- Accessed Network Adapter settings
- Modified DNS configuration to internal DNS server
- Flushed DNS resolver cache
- Tested name resolution and connectivity using ping

---

## Resolution
- Updated client DNS server to internal domain controller
- Cleared DNS cache using ipconfig /flushdns
- Verified connectivity to internal web server (web.homelab.local)
- Confirmed internal website loads successfully in browser

---

## Screenshots

### 1. Ticket (Spiceworks)
![Ticket](screenshots/ticket.png)

### 2. Reported Issue (Internal Site Not Reachable)
![Issue](screenshots/issue1.png)

### 3. External Connectivity Verified
![Issue](screenshots/issue2.png)

### 4. Troubleshooting Steps
![Troubleshooting](screenshots/troubleshooting1.png)
![Troubleshooting](screenshots/troubleshooting2.png)
![Troubleshooting](screenshots/troubleshooting3.png)
![Troubleshooting](screenshots/troubleshooting4.png)
![Troubleshooting](screenshots/troubleshooting5.png)
![Troubleshooting](screenshots/troubleshooting6.png)
![Troubleshooting](screenshots/troubleshooting7.png)

### 5. Issue Resolved (Working State)
![Resolved](screenshots/resolved.png)
