🎯 Objective

Configure basic firewall rules using UFW (Linux) and Windows Firewall to allow/deny specific ports.

🛠️ Tools

Linux: UFW

Windows: Windows Defender Firewall

✅ Key Commands

Linux (UFW)

sudo ufw enable
sudo ufw status numbered
sudo ufw deny 23       # Block Telnet
sudo ufw allow 22/tcp  # Allow SSH
sudo ufw delete deny 23  # Cleanup

Windows

Open Windows Firewall with Advanced Security

Add Inbound Rule → Port 23 → Block

Add Inbound Rule → Port 22 → Allow

🧪 Testing

Use telnet, ssh, or Test-NetConnection to verify port access.

🧹 Restore State

Remove added rules after testing to return system to its original state.
