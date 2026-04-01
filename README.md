# KramCom CTF - Mr. Robot themed Telecom CTF

![Mr. Robot](https://img.shields.io/badge/Theme-Mr.Robot-black?style=for-the-badge)  
A realistic **telecom surveillance** Capture The Flag environment inspired by Mr. Robot.

Built as a full vulnerable VM with a professional LAMP stack (Apache + MySQL + PHP). Players must perform web reconnaissance, brute-force, SQL injection, credential reuse, lateral movement, log analysis, and privilege escalation to capture all **7 flags**.

## Files Included
- **`KramCom-CTF.ova`** → Ready-to-import Virtual Machine (7 flags inside)
- **`Walkthrough.pdf`** → Complete step-by-step player walkthrough (for organizers / self-learning)

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
4. Login as user `tyrell` (password: tyrell123) if needed for admin tasks
5. Find the VM's IP address (`ip addr show` or check DHCP)
6. Start hacking from your Kali machine → `http://<VM-IP>`

**Total Flags:** 7 (scattered across web, files, logs, and root)

## Repository Contents (after you push)
- `KramCom-CTF.ova` (via Git LFS)
- `Walkthrough.pdf`
- `setup-manual-steps.md` *(optional – full manual setup guide)*
- This README

## Warning
This VM is intentionally vulnerable.  
Do **NOT** expose it to the internet or use it in production.

Made with ❤️ by Vikram for CTF lovers & offensive security enthusiasts.

---

**Happy Hacking!**  
Feel free to open an issue or PR if you want improvements.