🛡️ ***Linux Security Audit Script***

📌 Description (English)

Linux Security Audit Script is a Bash-based security auditing tool that collects detailed information about a Linux system.
It helps system administrators and security researchers during system auditing, monitoring, and hardening.

This script instantly gathers critical security-related data from the system and presents it in an organized way.


📌 বর্ণনা (বাংলা)

Linux Security Audit Script একটি Bash স্ক্রিপ্ট, যা Linux সিস্টেমের গুরুত্বপূর্ণ নিরাপত্তা সংক্রান্ত তথ্য সংগ্রহ করে।
এটি system hardening, security audit এবং monitoring–এর জন্য খুবই উপকারী।

স্ক্রিপ্টটি দ্রুত সিস্টেমের বিভিন্ন নিরাপত্তা অবস্থা যাচাই করে বিস্তারিত রিপোর্ট তৈরি করে।

🔍 Features / What This Script Checks:

🧾 System & Kernel Information

🐧 Linux Kernel Information

📦 Linux Distribution Information

🧮 CPU / System Information

📟 Kernel Messages

⏱️ Uptime Information

🔄 Last Reboots



👤 User & Authentication

👤 Current User and ID Information

👥 List Current Logged-in Users

👥 List User Names

👑 UID 0 users other than root

🚫 Check for Null Passwords

⏳ Password Aging

🧷 Password Policies

🔐 Failed Login Attempts

🐚 Shells Used by Users




🔐 Security & Hardening

🛡️ IPTables Information

🛡️ Sysctl Security Parameters

🧱 TCP Wrappers

🔐 SSH Configuration

🎭 MOTD Banner Message

⚠️ Dangerous Dotfiles




🌐 Network Information

🌐 Active Internet Connections & Open Ports

🌐 Network Interfaces

🛣️ IP Routing Table

🌐 ARP Table

⚙️ Network Parameters



🔧 Services & Processes

🔧 Running Services

🛠️ Services Run by Root

🧾 Running Processes

🕒 Cron Jobs



📦 Packages & Storage

📦 List All Installed Packages

🆙 Check Upgradable Packages

❗ Check for Broken Dependencies

💽 Check Available Disk Space

🧠 Check Memory Usage



📂 Files & Permissions

📂 World Writable Files

🧷 SUID / SGID Binaries

📁 Source List File Check



📜 Logs & History

📜 Command History



## ▶️ Usage 

*First of all 

git clone 

Then, 

cd Felcon

Step 1: Give Execute Permission
chmod +x LinuxAudit.sh

Step 2: Run the Script
./LinuxAudit.sh



## 🧪 Testing

✅ Tested on Debian OS

⚠️ May require root privileges for full audit results



## 📌 Notes

Run as root for complete and accurate security checks

Designed for educational, auditing, and hardening purposes only



## 📜 License

This project is open-source. You are free to modify and use it for learning and security auditing.