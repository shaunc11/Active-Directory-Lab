# 🛡️ Windows Server 2022 Active Directory Lab

This project simulates a small enterprise environment using **Windows Server 2022** and **Active Directory**. It was built to reinforce my understanding of domain management, user administration, and Group Policy configuration.

> 🔍 **Goal:** Create a fully functional AD lab to simulate real-world IT and helpdesk scenarios.

---

## 💻 Lab Setup

| Component         | Details                            |
|------------------|-------------------------------------|
| Virtualization    | Oracle VirtualBox                  |
| Domain Controller | Windows Server 2022                |
| Clients           | 2x Windows 10                      |
| Domain Name       | `skc11.com`                        |
| Network           | Host-Only Adapter + Static IPs     |

---

## ⚙️ Key Features + Skills Demonstrated

### 🧱 Active Directory Domain Services
- Promoted WS2022 to domain controller
- Created forest and static DNS
- Added OUs: `Helpdesk`, `IT`, `HR`

### 👥 User + Group Management
- Created users manually and via copy
- Enabled **Advanced Features** in ADUC for Attribute Editor
- Practiced account unlocks, password resets, expiration settings

### 🛡️ Group Policy Configuration
- Enforced password complexity, lockout policies
- Used GPMC to edit and link policies to domain
- Verified results with `gpresult /r` (RSOP)

### 🔧 Troubleshooting + Admin Tools
- `net user`, `ipconfig`, `ping`, and `net use` for network/user diagnostics
- Simulated account lockouts and computer “fall off domain”
- Joined clients to domain + installed RSAT for remote management

---

## 📂 Files Included

| File                            | Description                                      |
|---------------------------------|--------------------------------------------------|
| `Lab_Notes.md`                 | Cleaned write-up from my original lab work       |
| `Screenshots/`                 | Key screenshots: ADUC, RSOP, GPOs                |
| `User_Creation.ps1` (coming)   | PowerShell script for bulk user creation         |
| `RSOP_Report.txt`              | Sample Resultant Set of Policy output            |

---

## 🧠 Interview-Ready Takeaways

- I can build, manage, and troubleshoot Active Directory from scratch.
- I know how to use command-line tools for real-world diagnostics.
- I’ve enforced Group Policies and tracked their application using RSOP.
- I’ve documented everything clearly and reproducibly.

---

## 🔗 Related Resources

- 🎓 [My Portfolio Blog Post →](https://carrillocybercom.wordpress.com)  
- 🎥 [KevTech IT Support Playlist Used](https://www.youtube.com/playlist?list=PLdh13bXVc6-k_u2RPqYAp8R8HtYT_ONht)

---

> 🔐 Built by Shaun — aspiring SOC Analyst, lab builder, and cyber problem solver.
