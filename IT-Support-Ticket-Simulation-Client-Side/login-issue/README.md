# Login Issue

## Summary
User unable to log in to workstation.

## User
Olivia Martinez

## Department
HR

## Issue
User reports login failure and notices system appears different than usual.

---

## Troubleshooting
- Attempted login using domain credentials
- Observed authentication failure (invalid credentials)
- Identified login screen as local account (not domain)
- Determined system not joined to domain
- Logged in using local administrator account
- Navigated to system settings (About)
- Accessed domain join configuration
- Initiated domain join process
- Authenticated using domain administrator credentials
- Restarted system to apply changes

---

## Resolution
- Rejoined workstation to domain
- Restored domain authentication functionality
- Verified domain login screen appears on startup
- Confirmed user successfully logs in with domain credentials

---

## Screenshots

### 1. Ticket (Spiceworks)
![Ticket](screenshots/ticket.png)

### 2. Reported Issue
![Issue](screenshots/issue1.png)
![Issue](screenshots/issue2.png)

### 3. Troubleshooting Steps
![Troubleshooting](screenshots/troubleshooting1.png)
![Troubleshooting](screenshots/troubleshooting2.png)
![Troubleshooting](screenshots/troubleshooting3.png)

### 4. Issue Resolved (Working State)
![Resolved](screenshots/resolved1.png)
![Resolved](screenshots/resolved.png)
