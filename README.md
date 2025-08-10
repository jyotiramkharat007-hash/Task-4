# Task-4

# Task 4 – Setup and Use a Firewall on Kali Linux (UFW)

## Objective
Configure and test basic firewall rules to allow or block traffic using UFW on Kali Linux.

## Tools Used
- Kali Linux
- UFW (Uncomplicated Firewall)

## Steps Performed

### 1. Enable and Verify UFW
```bash
sudo apt update
sudo apt install ufw -y
sudo ufw enable
sudo ufw status verbose
sudo ufw deny 23/tcp
sudo ufw status numbered
sudo ufw allow 22/tcp
sudo ufw status numbered

sudo ufw delete 1
sudo ufw delete 2
sudo ufw status numbered
