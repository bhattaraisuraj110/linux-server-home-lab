# linux-server-home-lab
Ubuntu Server administration lab using UTM on Mac

## Project Overview
This project documents my first Linux server administration home lab using Ubuntu Server ARM64 on a MacBook Air M4 with UTM.

## Tools Used
- MacBook Air M4
- UTM
- Ubuntu Server ARM64
- Apache2
- OpenSSH Server
- UFW Firewall
- macOS Terminal

## What I Configured
- Installed Ubuntu Server in UTM
- Created Linux users
- Managed file permissions
- Installed Apache2 web server
- Configured UFW firewall
- Enabled SSH remote access
- Connected from macOS Terminal to Ubuntu Server using SSH

## Key Commands Used

```bash
hostname
uname -a
lsb_release -a
sudo apt update
sudo apt upgrade -y
sudo adduser testuser
sudo usermod -aG sudo testuser
id testuser
sudo apt install apache2 -y
sudo systemctl status apache2
sudo ufw enable
sudo ufw allow ssh
sudo ufw allow http
sudo ufw status
sudo apt install openssh-server -y
sudo systemctl status ssh
ip a
ssh suraj@192.168.64.4
