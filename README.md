# KramCom CTF - Mr. Robot themed Telecom CTF

![Mr. Robot](https://img.shields.io/badge/Theme-Mr.Robot-black?style=for-the-badge)  
A realistic **telecom surveillance** Capture The Flag environment inspired by Mr. Robot.

Built as a full vulnerable VM with a professional LAMP stack (Apache + MySQL + PHP). Players must perform web reconnaissance, brute-force, SQL injection, credential reuse, lateral movement, log analysis, and privilege escalation to capture all **7 flags**.

![image alt]()

## Download the VM

**KramCom.zip** (zipped OVA - ~3.7 GB original)  
→ Download from [https://drive.google.com/file/d/1IyQXVlSczmhqEecIZyxg5yBieAjKtfnR/view?usp=sharing](https://drive.google.com/file/d/1gy8cI8UKnXVyqWemgyU_nqE1tmDBtJlv/view?usp=drive_link)

**Walkthrough.pdf** → Available directly in this repository.

## Difficulty
**Medium**  
Ideal for beginners to intermediate players who know basic web attacks, SSH, and Linux privilege escalation.

## Learning Objectives
- Web enumeration (gobuster/dirb)
- Hidden admin panel + brute force / credential stuffing
- SQL Injection
- Password reuse & lateral movement (SSH)
- Log harvesting
- Sudo privilege escalation (NOPASSWD script abuse)

## How to Run the CTF

1. Download the `KramCom-CTF.ova` file
2. Import it into **VirtualBox** (recommended) or VMware
3. Start the VM
4. Find the VM's IP address (`ip addr show` or check DHCP)
5. Start hacking from your Kali machine → `http://<VM-IP>`

**Total Flags:** 7 (scattered across web, files, logs, and root)

## Warning
This VM is intentionally vulnerable.  
Do **NOT** expose it to the internet or use it in production.

Made with ❤️ by Vikram for CTF lovers & offensive security enthusiasts.

---

**Happy Hacking!**  
Feel free to open an issue or PR if you want improvements.
