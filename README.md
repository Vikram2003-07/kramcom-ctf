# KRAMCOM

Difficulty: Medium

![Mr. Robot](https://img.shields.io/badge/Theme-Mr.Robot-black?style=for-the-badge)

## Description
KRAMCOM is a telecom-themed CTF machine that simulates a realistic penetration testing engagement involving enumeration, authentication bypass, SQL injection, lateral movement, and privilege escalation.

Built as a full vulnerable VM with a professional LAMP stack (Apache + MySQL + PHP). Players must perform web reconnaissance, brute-force, SQL injection, credential reuse, lateral movement, log analysis, and privilege escalation to capture all **7 flags**.

![image alt](https://github.com/Vikram2003-07/kramcom-ctf/blob/90fef8c59d82326884d41929f51a7506eb141bd2/Kramcom.jpg)

## Download
Google Drive:
[https://drive.google.com/file/d/1fK0GZiqXcS5Zb--S1dpH5fqiUufkQ_gm/view?usp=sharing](https://drive.google.com/file/d/1fK0GZiqXcS5Zb--S1dpH5fqiUufkQ_gm/view?usp=sharing)

## Verify Integrity
**On Linux**
```bash
sha256sum KramCom.zip
```
**On Windows**
```bash
Get-Filehash "KramCom.zip" -Algorithm MD5
```

Expected SHA256:
`CDA9E15AA6F50F8BA3D89D79C349848729A2C04AA5C8339617397D4E208EB1D9`

## Walkthrough
Password-protected PDF included.

Hint:
My favorite One Piece character.

## Flags
7 Flags Total

## Learning Objectives
- Web enumeration (gobuster/dirb)
- Hidden admin panel + brute force / credential stuffing
- SQL Injection
- Password reuse & lateral movement (SSH)
- Log harvesting
- Sudo privilege escalation (NOPASSWD script abuse)

## How to Run the CTF
1. Download the `KramCom.zip` file
2. Extract the archive
3. Import the OVA into **VirtualBox** (recommended) or VMware
4. Start the VM
5. Find the VM's IP address (`ip addr show` or check DHCP)
6. Start hacking from your Kali machine: `http://<VM-IP>`

## Warning
This VM is intentionally vulnerable.
Do **NOT** expose it to the internet or use it in production.

## Author
Made with ❤️ by Vikram for CTF lovers & offensive security enthusiasts.

---

**Happy Hacking!**
Feel free to open an issue or PR if you want improvements.
