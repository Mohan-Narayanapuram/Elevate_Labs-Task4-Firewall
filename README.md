# Task 4 – macOS Firewall Configuration

## Objective:
Simulate basic traffic filtering using the built-in macOS Firewall by blocking and allowing specific applications and services.

## System Used:
- macOS Ventura
- System Settings > Firewall

## Steps Performed:
1. Enabled the Firewall from Network settings
2. Blocked incoming traffic for a chosen app (simulate port 23 block)
3. Allowed incoming traffic for Remote Login (SSH – port 22)
4. Restored original firewall state

## Screenshots:
- `firewall_enabled.png`
- `block_telnet_like_app.png`
- `allow_ssh_macos.png`
- `firewall_restored.png`

## Learnings:
- macOS firewall manages **inbound traffic**
- GUI offers simple rules per app, not raw port numbers
- Useful for understanding firewall concepts without terminal commands
