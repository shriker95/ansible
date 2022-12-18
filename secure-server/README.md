# Secure Server
Ein paar basics um einen Server abzusichern.

Es tut folgende Dinge:
 * Schaltet die Firewall ein
 * Erlaubt nur SSH Verbindungen
 * Installiert fail2ban mit default Settings (nur sshd)

## Vorrassetzungen
Installation von Ansible:
```bash
sudo apt install ansible -y
```