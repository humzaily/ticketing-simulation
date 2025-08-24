## Ticket 1: Password Reset
**Issue:** User cannot log in due to a forgotten password.

**Resolution:** Reset the user’s password via the directory service (Active Directory) and verify that the user can log in with the new credentials.

---

## Ticket 2: Printer Offline
**Issue:** The office printer is showing as offline.

**Resolution:** Check the printer’s network connection, restart the printer, and reinstall or update the printer driver. Confirm that the printer is online and printing.

---

## Ticket 3: Network Connectivity
**Issue:** User cannot access the internet.

**Resolution:** Check the IP configuration and renew the DHCP lease. Restart the network interface on the user’s computer, and verify connectivity using `ping` to a known address (e.g., 8.8.8.8).
