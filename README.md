
---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🎨 UI/UX
- ⚡ **Matrix Rain Background** animation
- ⌨️ **Terminal Typing Effect** on hero section
- 🌙 **Professional Dark Theme** throughout
- 📱 **Fully Responsive** — mobile, tablet, desktop
- 🎬 **AOS Scroll Animations** for smooth UX
- 🎯 **Unique color theme** per learning module
- 🔝 **Back to Top** floating button
- ⏳ **Loading Screen** animation on entry

</td>
<td width="50%">

### 🔧 Functionality
- 🔍 **Real-Time Search** with live filtering
- 📋 **One-Click Copy** for all commands
- 🔔 **Toast Notifications** on copy
- 📰 **Live Cybersecurity News Feed** (RSS)
- 🗂️ **News Category Filtering** (7 categories)
- 📡 **Breaking News Ticker** auto-scrolling
- 🔄 **Auto-Refresh** news every 10 minutes
- 📖 **Expand/Collapse All** sections

</td>
</tr>
<tr>
<td width="50%">

### 📚 Content
- 🐧 **100+ Linux Commands** categorized
- 🪟 **55+ Windows Commands** categorized
- 🗺️ **7 Attack Technique Modules**
- 📊 **OWASP Mobile Top 10** reference
- 🗺️ **Nmap 30+ Command** cheat sheet
- 🔑 **Port Reference Guide** (24 ports)
- 📖 **Google Dorking** operators table
- 🛡️ **Countermeasures** for every topic

</td>
<td width="50%">

### 🛡️ Security Education
- ⚠️ **Legal disclaimers** on all sensitive topics
- 📝 **CEH methodology** alignment
- 🔒 **OWASP** standards references
- 🌐 **External resources** linked throughout
- 📚 **Book recommendations** included
- 🛠️ **Tool descriptions** with real commands
- 📋 **Structured learning path** provided
- 🔄 **Offense & Defense** balanced content

</td>
</tr>
</table>

---

## 🗂️ Project Structure

```bash
hackers-world/
│
├── 📄 index.html              # 🏠 Home — Landing page with news feed
├── 📄 Linux_cmd.html          # 🐧 Linux Commands (100+ commands)
├── 📄 win-cmd.html            # 🪟 Windows Commands (55+ commands)
├── 📄 footprinting.html       # 🔍 Footprinting & Reconnaissance
├── 📄 scanning.html           # 📡 Network Scanning (Nmap cheat sheet)
├── 📄 system-hacking.html     # 💻 System Hacking & Exploitation
├── 📄 android-hacking.html    # 📱 Android Security Testing
├── 📄 ddos.html               # ⚡ DDoS Attacks & Mitigation
├── 📄 mitm.html               # 🕵️ Man-in-the-Middle Attacks
├── 📄 wifi-hacking.html       # 📶 WiFi Security Testing
│
├── 📁 books/                  # 📚 Reference PDF materials
│   ├── 📕 CEH v9 Certified Ethical Hacker Version 9.pdf
│   ├── 📗 The art of deception.pdf
│   └── 📘 python.pdf
│
└── 📄 README.md               # 📋 You are here!


📚 Content Modules
<div align="center">
#	Page	Theme	Difficulty	Key Content
01	🏠 index.html	🟢 Green	—	Home, Matrix BG, Live News, Learning Path
02	🐧 Linux_cmd.html	🟢 Green	🟢 Beginner	15 categories, 100+ commands, live search
03	🪟 win-cmd.html	🔵 Cyan	🟢 Beginner	14 categories, 55+ commands, live search
04	🔍 footprinting.html	🟡 Amber	🟡 Intermediate	WHOIS, DNS, OSINT, Google Dorking, 9 tools
05	📡 scanning.html	🟣 Purple	🟡 Intermediate	Nmap 30+ cmds, port reference, 9 scan types
06	💻 system-hacking.html	🔴 Red	🔴 Advanced	PrivEsc, Metasploit, Password cracking
07	📱 android-hacking.html	🟢 Emerald	🔴 Advanced	APK analysis, Frida, ADB, OWASP Mobile
08	⚡ ddos.html	🟠 Orange	🟡 Intermediate	3 attack categories, iptables, Nginx config
09	🕵️ mitm.html	🩷 Pink	🔴 Advanced	ARP spoofing, Bettercap, SSL stripping
10	📶 wifi-hacking.html	🩵 Cyan	🔴 Advanced	Aircrack-ng, WPA cracking, Evil Twin, WPS
</div>
🛠️ Tech Stack
<div align="center">
Technology	Version	Purpose
HTML5	5	Structure & Content
CSS3	3	Styling & Animations
JavaScript	ES6+	Interactivity & Logic
Bootstrap	4.3.1	Responsive Grid
Bootstrap Icons	1.10.2	Icon Library
Google Fonts	—	Poppins + Fira Code
AOS	2.3.1	Scroll Animations
RSS2JSON	API	News Feed
</div>
✅ Zero dependencies — No npm, no build tools, no Node.js required!
Just open in a browser and it works.

🎨 Design System
<div align="center">
Color Palette Per Module
Module	Primary Color	Hex Code
🏠 Home / Linux	Cyber Green	#00ff88
🪟 Windows	Ocean Cyan	#00b4d8
🔍 Footprinting	Amber Gold	#f59e0b
📡 Scanning	Electric Purple	#a855f7
💻 System Hacking	Danger Red	#ef4444
📱 Android	Emerald Green	#34d399
⚡ DDoS	Blazing Orange	#f97316
🕵️ MITM	Hot Pink	#ec4899
📶 WiFi	Electric Blue	#06b6d4
</div>
Global Dark Theme Variables
CSS

:root {
  --dark:           #0d1117;   /* Main background        */
  --darker:         #010409;   /* Footer / deepest BG    */
  --card-bg:        #161b22;   /* Card surfaces          */
  --text-primary:   #c9d1d9;   /* Primary text           */
  --text-secondary: #8b949e;   /* Secondary text         */
  --accent:         #58a6ff;   /* Links & accents        */
  --border:         #30363d;   /* Borders & dividers     */
}
Typography
text

Headings  →  Poppins     (300, 400, 500, 600, 700)
Body      →  Poppins     (400)
Code      →  Fira Code   (monospace)
🚀 Getting Started
Prerequisites
Bash

# No prerequisites needed!
# Just a modern web browser:
✅ Chrome 90+
✅ Firefox 88+
✅ Safari 14+
✅ Edge 90+
Installation
Option 1: Clone the repository

Bash

# Clone the repo
git clone https://github.com/A-Trident/hackers-world.git

# Navigate to the project
cd hackers-world

# Open in browser (macOS)
open index.html

# Open in browser (Linux)
xdg-open index.html

# Open in browser (Windows)
start index.html
Option 2: Download ZIP

Bash

# Download from GitHub
# Click: Code → Download ZIP → Extract → Open index.html
Option 3: GitHub Pages

Bash

# 1. Fork this repository
# 2. Go to Settings → Pages
# 3. Select branch: main, folder: / (root)
# 4. Visit: https://A-Trident.github.io/hackers-world
Option 4: Local Development Server

Bash

# Using Python (recommended)
python3 -m http.server 8080
# Then visit: http://localhost:8080

# Using VS Code
# Install "Live Server" extension → Right click index.html → Open with Live Server
📸 Screenshots
<div align="center">
🏠 Home Page
text

┌─────────────────────────────────────────────────────────┐
│  🛡️ HACKER'S WORLD              Home Topics Resources ≡ │
├─────────────────────────────────────────────────────────┤
│                                                         │
│         [ Ethical Hacking & Cybersecurity ]             │
│                                                         │
│      Learn Ethical Hacking                              │
│         The Right Way                                   │
│                                                         │
│   [ Start Learning ]    [ Resources ]                   │
│                                                         │
│   ┌─────────────────────────────────────┐               │
│   │ terminal                            │               │
│   │ root@hackerworld:~$ nmap -sV -O ... │               │
│   │                        █            │               │
│   └─────────────────────────────────────┘               │
│                                                         │
└─────────────────────────────────────────────────────────┘
🔍 Search Feature
text

┌─────────────────────────────────────────────────────────┐
│                                                         │
│   🔍 Search commands... (e.g., nmap, grep, chmod)  ✕   │
│                                                         │
│   Found 12 command(s) in 4 categories                   │
│                                                         │
│   ┌ Networking ──────────────── 3 ┐                     │
│   │ ✦ ifconfig -a         [Copy] │                     │
│   │ ✦ netstat -nutlp      [Copy] │                     │
│   └───────────────────────────── ┘                     │
│                                                         │
└─────────────────────────────────────────────────────────┘
📰 Live News Feed
text

┌─────────────────────────────────────────────────────────┐
│  ⚡ BREAKING  Major Ransomware → New CVE Found → ...    │
├─────────────────────────────────────────────────────────┤
│  [All] [Hacking] [Crypto] [Dark Web] [Breaches] [More]  │
├─────────────────────────────────────────────────────────┤
│  ┌──────────┐  ┌──────────┐  ┌──────────┐              │
│  │ 🔴BREACH │  │🟢HACKING │  │🟡 CRYPTO │              │
│  │          │  │          │  │          │              │
│  │ Title... │  │ Title... │  │ Title... │              │
│  │ Desc...  │  │ Desc...  │  │ Desc...  │              │
│  │ 📻 THN   │  │ 📻 BC    │  │ 📻 Krebs │              │
│  │ 🕐 2h ago│  │ 🕐 5h ago│  │ 🕐 1d ago│              │
│  └──────────┘  └──────────┘  └──────────┘              │
└─────────────────────────────────────────────────────────┘
</div>
🗺️ Learning Path
text

BEGINNER                    INTERMEDIATE                  ADVANCED
────────                    ────────────                  ────────
    │                            │                            │
    ▼                            ▼                            ▼
┌─────────┐              ┌─────────────┐             ┌──────────────┐
│  Linux  │              │Footprinting │             │System Hacking│
│Commands │──────────────│    &        │─────────────│  PrivEsc     │
│   🐧    │              │   Recon 🔍  │             │  Metasploit  │
└─────────┘              └─────────────┘             └──────────────┘
    │                            │                            │
    ▼                            ▼                            ▼
┌─────────┐              ┌─────────────┐             ┌──────────────┐
│Windows  │              │  Network    │             │  Android     │
│Commands │              │  Scanning   │             │  Hacking 📱  │
│   🪟    │              │   Nmap 📡   │             │  OWASP       │
└─────────┘              └─────────────┘             └──────────────┘
                                                            │
                                                            ▼
                                               ┌──────────────────────┐
                                               │  DDoS ⚡ → MITM 🕵️  │
                                               │  WiFi Hacking 📶     │
                                               └──────────────────────┘
⚠️ Legal Disclaimer
<div align="center">
text

╔══════════════════════════════════════════════════════════════╗
║                    ⚠️  IMPORTANT NOTICE  ⚠️                   ║
╠══════════════════════════════════════════════════════════════╣
║                                                              ║
║  All content in this project is provided STRICTLY for        ║
║  educational and informational purposes only.                ║
║                                                              ║
║  ✅ DO: Learn, study, and practice on your own systems       ║
║  ✅ DO: Use in authorized CTF competitions                   ║
║  ✅ DO: Apply in professional penetration testing (with      ║
║         written authorization)                               ║
║  ✅ DO: Share knowledge responsibly                          ║
║                                                              ║
║  ❌ DON'T: Use techniques on systems you don't own           ║
║  ❌ DON'T: Access networks without written permission        ║
║  ❌ DON'T: Use for malicious or illegal purposes             ║
║                                                              ║
║  Unauthorized use may violate:                               ║
║  • Computer Fraud and Abuse Act (CFAA) — USA                 ║
║  • Computer Misuse Act (CMA) — UK                            ║
║  • Information Technology Act — India                        ║
║  • Cybercrime laws in your jurisdiction                      ║
║                                                              ║
║  The authors bear NO responsibility for misuse.              ║
╚══════════════════════════════════════════════════════════════╝
</div>
🤝 Contributing
Contributions make the open-source community an amazing place to learn and grow!
Any contributions you make are greatly appreciated.

Bash

# Step 1: Fork the repository
# Click the "Fork" button at the top right of this page

# Step 2: Clone your fork
git clone https://github.com/A-Trident/hackers-world.git

# Step 3: Create a feature branch
git checkout -b feature/AmazingFeature

# Step 4: Make your changes
# Edit files, add content, fix bugs...

# Step 5: Commit your changes
git add .
git commit -m "✨ Add: Amazing new feature"

# Step 6: Push to your branch
git push origin feature/AmazingFeature

# Step 7: Open a Pull Request
# Go to GitHub → Your Fork → Pull Requests → New Pull Request
💡 Ways to Contribute
text

📝 Content      → Add new commands, tools, or techniques
🐛 Bug Fix      → Fix broken links, typos, or code errors
🎨 Design       → Improve UI/UX or add new themes
📚 Docs         → Improve README or add inline documentation
🔒 Security     → Report vulnerabilities responsibly
Commit Message Convention
Bash

✨ Add:      New feature or content
🐛 Fix:      Bug fix
🎨 Style:    UI/Design changes
📝 Docs:     Documentation updates
♻️ Refactor: Code refactoring
🔒 Sec:      Security improvements
⚡ Perf:     Performance improvements
📊 Project Stats
<div align="center">
GitHub stars
GitHub forks
GitHub issues
GitHub last commit

text

📊 Project Statistics
├── 📄 Total Pages          : 10 HTML Files
├── 💻 Total Commands       : 155+ (Linux + Windows)
├── 🛡️  Security Modules    : 7 Attack Domains
├── 📰 News Sources         : 4 Live RSS Feeds
├── 🏷️  News Categories     : 7 (Hacking, Crypto, etc.)
├── 🎨 Unique Color Themes  : 9 (one per module)
├── 📋 Copy-able Commands   : 200+
├── 📚 Reference Tables     : 15+
└── 🌐 External Resources   : 25+
</div>
📄 License
text

MIT License

Copyright (c) 2024 Abhinav Kumar

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
License: MIT

👤 Author
<div align="center">
Abhinav Kumar

GitHub
LinkedIn

</div>
🙏 Acknowledgments
<div align="center">
Resource	Purpose
The Hacker News	Live news feed source
BleepingComputer	Security news feed
KrebsOnSecurity	Security research feed
Dark Reading	Cybersecurity news feed
OWASP	Security standards reference
Offensive Security	Kali Linux & methodology
Bootstrap	CSS framework
Bootstrap Icons	Icon library
AOS Library	Scroll animations
Google Fonts	Poppins & Fira Code
Capsule Render	README header
Shields.io	README badges
DemoLab Typing SVG	Terminal animation
RSS2JSON	RSS feed API
GTFOBins	PrivEsc reference
ExplainShell	Command explanations
</div>
🌟 Support The Project
<div align="center">
If this project helped you learn something new, please consider:

⭐ Starring the repository — It helps others discover this project

🍴 Forking & Contributing — Help improve the content

📢 Sharing — Tell your security community about it

</div>
<div align="center"><img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00b4d8,100:00ff88&height=120&section=footer&animation=fadeIn"/>
text

root@hackerworld:~$ echo "Happy Hacking — Ethically! 🛡️"
Happy Hacking — Ethically! 🛡️

root@hackerworld:~$ █
Made with ❤️ for the cybersecurity community

"Knowledge is power. Use it responsibly."

Visitor Count

</div> ```



