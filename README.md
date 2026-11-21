<div align="center">

# ⚡ SHANNU

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=26&duration=3000&pause=1000&color=00FFAA&center=true&vCenter=true&width=800&lines=Cybersecurity+Engineer;AI+Builder;CTF+Player;Arch+Linux+User;Building+AI+for+Security;Always+Learning..." />

<br>

[![Writeups](https://img.shields.io/badge/Walkthroughs-40-00FFAA?style=for-the-badge&logo=bookstack&logoColor=black)](https://github.com/5h4nnu-dev/CTF-Archive)
[![Commits](https://img.shields.io/github/commit-activity/t/5h4nnu-dev/CTF-Archive?style=for-the-badge&color=38BDF8)](https://github.com/5h4nnu-dev/CTF-Archive/commits/main)
[![Screenshots](https://img.shields.io/badge/Screenshots-476-A855FA?style=for-the-badge&logo=image&logoColor=white)](https://github.com/5h4nnu-dev/CTF-Archive/tree/main/public/assets/screenshots)
[![Stars](https://img.shields.io/github/stars/5h4nnu-dev/CTF-Archive?style=for-the-badge&color=FBBF24)](https://github.com/5h4nnu-dev/CTF-Archive/stargazers)

### 📦 [github.com/5h4nnu-dev/CTF-Archive](https://github.com/5h4nnu-dev/CTF-Archive)

</div>

---

# > whoami

```bash
$ whoami

Name        : Shannu
Location    : India
Role        : Security Engineer
Focus       : AI + Cybersecurity

Mission

Build intelligent systems capable of finding,
understanding and fixing vulnerabilities automatically.
```

---

# Current Status

```text
██████████████████████████████████████

STATUS

🟢 ONLINE

MISSION

Building the future of AI-powered Security.

██████████████████████████████████████
```

---

# 🏆 Featured Project — CTF-Archive

<div align="center">

[![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-8-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vite.dev/)
[![react-markdown](https://img.shields.io/badge/react--markdown-10-000000?style=for-the-badge&logo=markdown&logoColor=white)](https://github.com/remarkjs/react-markdown)
[![Oxlint](https://img.shields.io/badge/Oxlint-1.69-7C3AED?style=for-the-badge)](https://oxc.rs/docs/guide/usage/linter.html)

</div>

**CTF-Archive** is a dark-themed React + Vite blog that turns my hands-on CTF lab work into searchable, screenshot-rich technical walkthroughs. Every room is documented with the same discipline: **overview → enumeration → exploitation → privilege escalation → flags → commands used → lessons learned → references**.

| 📊 Metric | Value |
| :--- | ---: |
| 📝 Walkthroughs | **40** rooms & challenges |
| 🗓 Development window | **Jul – Nov 2026** |
| 🔀 Commits | **43** (24 in Jul · 5 in Aug · 14 in Nov) |
| 🖼 Screenshots & diagrams | **476** |
| 📄 Written content | **~11,300** lines of Markdown |
| 🎯 Difficulty spread | 32 Easy · 5 Medium · 1 Hard · 1 Very Easy · 1 Learning |

## 🧠 What the archive covers

| Domain | Skills documented | Example rooms |
| :--- | :--- | :--- |
| 🌐 Web & CMS exploitation | Webmin backdoors, CMS RCE, SQLi, file upload, command injection | AttackerKB, Source, Bolt, Ignite, Thompson, Room 404 |
| 🔐 Privilege escalation | Sudo/GTFOBins, SUID, cron jobs, capabilities, PATH hijacking, containers | Wgel, Overpass, Kenobi, Kiba, Couch, Simple CTF |
| 🕵 OSINT & social engineering | Gravatar hashing, SOCMINT, metadata, public clue chains | The Brochure, Overheard at Breakfast, OhSINT |
| 🖼 Steganography & forensics | Image headers, binary decoding, packet captures, spectrograms | Madness, Lian_Yu, Jack, KoTH Food, CTF Collection Vol. 1 |
| 💥 Binary exploitation & CVEs | Buffer overflow, ret2win, Java deserialization, UAC bypass | The Cod Caper, Tony the Tiger, Blaster, Ice |
| 📚 Learning & custom tooling | Linux privesc lab, sqlmap tamper script, guided pentest path | Linux PrivEsc, Tamper, Path |

## ✨ App features

- 🔎 **Full-text search** across titles, descriptions and tags
- 🏷 **Difficulty & multi-tag filtering** (Easy → Insane, tags combinable)
- 📖 **Distraction-free detail view** with syntax-highlighted Markdown
- ✍ **In-app authoring** with YAML frontmatter and `localStorage` persistence
- ⬇ **One-click Markdown export** of any writeup
- 🌙 **Responsive dark UI** — glassmorphism navbar, smooth transitions, color-coded difficulty badges
- 🗂 **File-based content** — `import.meta.glob` loads `src/writeups/*.md` at build time

## 🔗 The attack-chain pattern behind every post

```text
RECON        ENUMERATE      EXPLOIT        FOOTHOLD       ESCALATE       LOOT        TEACH
  │              │             │              │              │            │           │
 nmap        gobuster      CVE / web     reverse shell   sudo / SUID   user & root   writeup
 ports       directories   injection     credentials     cron / PATH    flags       lessons
```

<details>
<summary>📚 <b>Open the full 40-room index</b> (click to expand)</summary>

| # | Room | Primary focus |
| :-- | :--- | :--- |
| 01 | [Anonforce](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/anonforce.md) | Anonymous FTP, PGP key cracking, root hash |
| 02 | [AttackerKB](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/attackerkb.md) | Webmin 1.890 supply-chain RCE (CVE-2019-15107) |
| 03 | [Blaster](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/blaster.md) | RDP credentials, Windows UAC bypass |
| 04 | [Blueprint](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/blueprint.md) | Rejetto HFS exploitation, privilege escalation |
| 05 | [Bolt](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/bolt.md) | Bolt CMS 3.7.1 authenticated RCE |
| 06 | [Brooklyn Nine Nine](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/brooklynninenine.md) | FTP, steganography, brute force, GTFOBins |
| 07 | [c4ptur3-th3-fl4g](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/capturetheflag.md) | Encoding, stego, spectrogram, forensics |
| 08 | [Couch](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/couch.md) | CouchDB exposure, Docker API, SSH tunneling |
| 09 | [CTF Collection Vol. 1](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/ctfcollectionvol1.md) | 20 standalone mini-challenges |
| 10 | [Dav](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/dav.md) | WebDAV webshell upload, sudo cat abuse |
| 11 | [Develpy](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/develpy.md) | Python `input()` injection, cron abuse |
| 12 | [Easy Peasy](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/easypeasy.md) | Web enumeration, GOST hashes, cron privesc |
| 13 | [KoTH Food CTF](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/food.md) | Command injection, SUID screen, sudo CVE |
| 14 | [Fowsniff](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/fowsniff.md) | OSINT, MD5 cracking, POP3, writable MOTD |
| 15 | [Ice](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/ice.md) | Icecast CVE-2004-1561, UAC bypass, Mimikatz |
| 16 | [Ignite](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/ignite.md) | Fuel CMS RCE (CVE-2018-16763) |
| 17 | [Jack](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/jack.md) | Swapped ports, layered encodings, SUID strings |
| 18 | [Kenobi](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/kenobi.md) | SMB, ProFTPD mod_copy, NFS, PATH hijack |
| 19 | [Kiba](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/kiba.md) | Kibana prototype pollution, Linux capabilities |
| 20 | [LazyAdmin](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/lazyadmin.md) | SweetRice backup disclosure, sudo Perl |
| 21 | [Lian_Yu](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/lianyu.md) | Base58, PNG header repair, stego, pkexec |
| 22 | [Library](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/library.md) | SSH brute force, sudo script replacement |
| 23 | [Linux PrivEsc](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/linuxprivesc.md) | 10+ privesc vectors in one learning VM |
| 24 | [Madness](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/madness.md) | Header repair, ROT13, SUID screen 4.5.0 |
| 25 | [OhSINT](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/ohsint.md) | Pure OSINT reconnaissance |
| 26 | [Overheard at Breakfast](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/overheardatbreakfast.md) | Discord leak → Gravatar hash → hidden flag |
| 27 | [Overpass](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/overpass.md) | Cookie bypass, SSH key cracking, `/etc/hosts` cron |
| 28 | [Path](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/path.md) | IDOR, upload bypass, UnrealIRCd backdoor |
| 29 | [Pickle Rick](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/picklerick.md) | `robots.txt`, command injection, passwordless sudo |
| 30 | [Room 404](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/room404.md) | Exposed `.git` repository reconstruction |
| 31 | [RootMe](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/rootme.md) | File upload, Python library privesc |
| 32 | [Simple CTF](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/simplectf.md) | CMS Made Simple SQLi, vim sudo |
| 33 | [Smag Grotto](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/smaggrotto.md) | PCAP credentials, cron SSH-key swap |
| 34 | [Source](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/source.md) | Webmin 1.890 backdoor, Perl injection |
| 35 | [Tamper](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/tamper.md) | Custom sqlmap tamper for auth-gated SQLi |
| 36 | [The Brochure](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/thebrochure.md) | Instagram SOCMINT, Base64 fragments |
| 37 | [The Cod Caper](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/thecodcaper.md) | SQLi, GDB ret2win buffer overflow |
| 38 | [Thompson](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/thompson.md) | Tomcat WAR deployment, world-writable cron |
| 39 | [Tony the Tiger](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/tonythetiger.md) | JBoss Java deserialization (CVE-2015-7501) |
| 40 | [Wgel](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/wgel.md) | Exposed SSH key, sudo `wget` privesc |

</details>

---

# Projects

| Project | Description |
|----------|-------------|
| 🛡 Vulnix | AI-powered vulnerability scanner |
| 🔍 SecureProbe | Web security assessment toolkit |
| 🤖 Emotional AI | AI that understands personality & emotions |
| 🎓 ARIS | AI campus surveillance system |
| 👥 AI Team | Autonomous AI Agents |
| 📝 [CTF-Archive](https://github.com/5h4nnu-dev/CTF-Archive) | 40-room CTF writeup blog — React + Vite |

---

# Cyber Arsenal

```text
Recon

██████████████████

Networking

██████████████████

Linux

██████████████████

Python

███████████████

TypeScript

██████████████

Cloud

██████████

Reverse Engineering

████████

Malware Analysis

██████

Artificial Intelligence

██████████████████
```

---

# Current Mission

```yaml
Learning

- Malware Analysis

- Reverse Engineering

- Kubernetes

- Cloud Security

- AI Agents

Building

- Vulnix

- SecureProbe

- Emotional AI

- AI Team

Goal

Become a Security Engineer building autonomous AI systems.
```

---

# Tech Stack

<p align="center">

<img src="https://skillicons.dev/icons?i=python,cpp,c,java,bash,ts,js"/>

<br>

<img src="https://skillicons.dev/icons?i=linux,docker,kubernetes,git,github,nginx"/>

</p>

---

# GitHub Statistics

<p align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=5h4nnu-dev&show_icons=true&theme=tokyonight&hide_border=true"/>

<img height="170" src="https://github-readme-streak-stats.herokuapp.com/?user=5h4nnu-dev&theme=tokyonight&hide_border=true"/>

</p>

---

# Languages

<p align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=5h4nnu-dev&layout=compact&theme=tokyonight&hide_border=true"/>

</p>

---

# Contribution Graph

<p align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=5h4nnu-dev&theme=tokyo-night"/>

</p>

---

# Trophy Cabinet

<p align="center">

<img src="https://github-profile-trophy.vercel.app/?username=5h4nnu-dev&theme=algolia&no-frame=true&column=4"/>

</p>

---

# Random Quote

> "Hack to understand. Build to protect."

---

<div align="center">

![](https://komarev.com/ghpvc/?username=5h4nnu-dev&color=00ffaa)

Thanks for stopping by. ⭐ the repos if they helped you.

</div>
 shannu@arch  ~/Templates/portfolio  ls
README-NEW.md  README.md  claude-README.md  shannu-portfolio
 shannu@arch  ~/Templates/portfolio  cat claude-README.md 
<!-- ============================================================ -->
<!--                  SHANNU · PROFILE README                     -->
<!-- ============================================================ -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20,24&height=230&section=header&text=SHANNU&fontSize=82&fontColor=00FFAA&fontAlignY=36&animation=fadeIn&desc=Cybersecurity%20Engineer%20%C2%B7%20AI%20Builder%20%C2%B7%20CTF%20Player&descSize=20&descColor=E2E8F0&descAlignY=58" width="100%" alt="Shannu banner" />

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=24&duration=3000&pause=1000&color=00FFAA&center=true&vCenter=true&width=800&height=50&lines=Cybersecurity+Engineer;AI+Builder;CTF+Player;Arch+Linux+User;Building+AI+for+Security;Always+Learning..." alt="Typing animation" />

<br>

![Status](https://img.shields.io/badge/STATUS-ONLINE-00FFAA?style=for-the-badge&logo=statuspage&logoColor=black&labelColor=0D1117)
![Location](https://img.shields.io/badge/LOCATION-INDIA-38BDF8?style=for-the-badge&logo=googlemaps&logoColor=white&labelColor=0D1117)
![Focus](https://img.shields.io/badge/FOCUS-AI%20%2B%20SECURITY-A855F7?style=for-the-badge&logo=hackthebox&logoColor=white&labelColor=0D1117)
![OS](https://img.shields.io/badge/OS-ARCH%20LINUX-FBBF24?style=for-the-badge&logo=archlinux&logoColor=black&labelColor=0D1117)

<br>

[![Writeups](https://img.shields.io/badge/Walkthroughs-40-00FFAA?style=for-the-badge&logo=bookstack&logoColor=black)](https://github.com/5h4nnu-dev/CTF-Archive)
[![Commits](https://img.shields.io/github/commit-activity/t/5h4nnu-dev/CTF-Archive?style=for-the-badge&color=38BDF8&logo=git&logoColor=white)](https://github.com/5h4nnu-dev/CTF-Archive/commits/main)
[![Screenshots](https://img.shields.io/badge/Screenshots-476-A855F7?style=for-the-badge&logo=image&logoColor=white)](https://github.com/5h4nnu-dev/CTF-Archive/tree/main/public/assets/screenshots)
[![Stars](https://img.shields.io/github/stars/5h4nnu-dev/CTF-Archive?style=for-the-badge&color=FBBF24&logo=github&logoColor=black)](https://github.com/5h4nnu-dev/CTF-Archive/stargazers)

### 📦 [github.com/5h4nnu-dev/CTF-Archive](https://github.com/5h4nnu-dev/CTF-Archive)

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=3" width="100%" alt="divider" />

## 👨‍💻nbsp;`> whoami`

<table>
<tr>
<td width="55%" valign="top">

```bash
$ whoami

Name     : Shannu
Location : India
Role     : Security Engineer
Focus    : AI + Cybersecurity
OS       : Arch Linux (btw)
```

</td>
<td width="45%" valign="top">

### 🎯 Mission

> Build intelligent systems capable of **finding**, **understanding** and **fixing** vulnerabilities — *automatically*.

![Online](https://img.shields.io/badge/🟢_STATUS-ONLINE-00FFAA?style=flat-square&labelColor=0D1117)
![Building](https://img.shields.io/badge/🚀_BUILDING-AI--POWERED_SECURITY-A855F7?style=flat-square&labelColor=0D1117)

</td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=3" width="100%" alt="divider" />

## 🏆 &nbsp;Featured Project — CTF-Archive

<div align="center">

[![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-8-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vite.dev/)
[![react-markdown](https://img.shields.io/badge/react--markdown-10-000000?style=for-the-badge&logo=markdown&logoColor=white)](https://github.com/remarkjs/react-markdown)
[![Oxlint](https://img.shields.io/badge/Oxlint-1.69-7C3AED?style=for-the-badge)](https://oxc.rs/docs/guide/usage/linter.html)

<a href="https://github.com/5h4nnu-dev/CTF-Archive">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=5h4nnu-dev&repo=CTF-Archive&theme=tokyonight&hide_border=true&show_owner=true" alt="CTF-Archive repo card" />
</a>

</div>

**CTF-Archive** is a dark-themed React + Vite blog that turns my hands-on CTF lab work into searchable, screenshot-rich technical walkthroughs. Every room is documented with the same discipline:

<div align="center">

`overview` ➜ `enumeration` ➜ `exploitation` ➜ `privilege escalation` ➜ `flags` ➜ `commands used` ➜ `lessons learned` ➜ `references`

</div>

### 📊 By the numbers

<div align="center">

| 📝 Walkthroughs | 🗓 Dev window | 🔀 Commits | 🖼 Screenshots | 📄 Markdown |
| :---: | :---: | :---: | :---: | :---: |
| **40** rooms | **Jul – Nov 2026** | **43** | **476** | **~11,300** lines |

![Easy](https://img.shields.io/badge/Easy-32-22C55E?style=for-the-badge)
![Medium](https://img.shields.io/badge/Medium-5-F59E0B?style=for-the-badge)
![Hard](https://img.shields.io/badge/Hard-1-EF4444?style=for-the-badge)
![Very Easy](https://img.shields.io/badge/Very_Easy-1-14B8A6?style=for-the-badge)
![Learning](https://img.shields.io/badge/Learning-1-A855F7?style=for-the-badge)

<sub>🔀 Commit history: **24** in Jul · **5** in Aug · **14** in Nov</sub>

</div>

### 🧠 What the archive covers

| Domain | Skills documented | Example rooms |
| :--- | :--- | :--- |
| 🌐 **Web & CMS exploitation** | Webmin backdoors, CMS RCE, SQLi, file upload, command injection | AttackerKB, Source, Bolt, Ignite, Thompson, Room 404 |
| 🔐 **Privilege escalation** | Sudo/GTFOBins, SUID, cron jobs, capabilities, PATH hijacking, containers | Wgel, Overpass, Kenobi, Kiba, Couch, Simple CTF |
| 🕵 **OSINT & social engineering** | Gravatar hashing, SOCMINT, metadata, public clue chains | The Brochure, Overheard at Breakfast, OhSINT |
| 🖼 **Steganography & forensics** | Image headers, binary decoding, packet captures, spectrograms | Madness, Lian_Yu, Jack, KoTH Food, CTF Collection Vol. 1 |
| 💥 **Binary exploitation & CVEs** | Buffer overflow, ret2win, Java deserialization, UAC bypass | The Cod Caper, Tony the Tiger, Blaster, Ice |
| 📚 **Learning & custom tooling** | Linux privesc lab, sqlmap tamper script, guided pentest path | Linux PrivEsc, Tamper, Path |

### ✨ App features

<table>
<tr>
<td>

🔎 **Full-text search**<br><sub>titles, descriptions & tags</sub>

</td>
<td>

🏷 **Smart filtering**<br><sub>Easy → Insane, combinable tags</sub>

</td>
<td>

📖 **Reader view**<br><sub>syntax-highlighted Markdown</sub>

</td>
</tr>
<tr>
<td>

✍ **In-app authoring**<br><sub>YAML frontmatter + `localStorage`</sub>

</td>
<td>

⬇ **One-click export**<br><sub>download any writeup as Markdown</sub>

</td>
<td>

🌙 **Dark responsive UI**<br><sub>glassmorphism navbar, colour-coded badges</sub>

</td>
</tr>
</table>

> 🗂 **File-based content** — `import.meta.glob` loads `src/writeups/*.md` at build time.

### 🔗 The attack-chain pattern behind every post

```mermaid
flowchart LR
    A([🔍 RECON<br/>nmap · ports]) --> B([📂 ENUMERATE<br/>gobuster · dirs])
    B --> C([💥 EXPLOIT<br/>CVE · web injection])
    C --> D([🐚 FOOTHOLD<br/>reverse shell · creds])
    D --> E([⬆ ESCALATE<br/>sudo · SUID · cron · PATH])
    E --> F([🚩 LOOT<br/>user & root flags])
    F --> G([📝 TEACH<br/>writeup · lessons])

    style A fill:#0D1117,stroke:#00FFAA,color:#00FFAA
    style B fill:#0D1117,stroke:#38BDF8,color:#38BDF8
    style C fill:#0D1117,stroke:#EF4444,color:#EF4444
    style D fill:#0D1117,stroke:#FBBF24,color:#FBBF24
    style E fill:#0D1117,stroke:#A855F7,color:#A855F7
    style F fill:#0D1117,stroke:#22C55E,color:#22C55E
    style G fill:#0D1117,stroke:#F472B6,color:#F472B6
```

<details>
<summary>📚 <b>Open the full 40-room index</b> (click to expand)</summary>

<br>

| # | Room | Primary focus |
| :-- | :--- | :--- |
| 01 | [Anonforce](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/anonforce.md) | Anonymous FTP, PGP key cracking, root hash |
| 02 | [AttackerKB](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/attackerkb.md) | Webmin 1.890 supply-chain RCE (CVE-2019-15107) |
| 03 | [Blaster](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/blaster.md) | RDP credentials, Windows UAC bypass |
| 04 | [Blueprint](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/blueprint.md) | Rejetto HFS exploitation, privilege escalation |
| 05 | [Bolt](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/bolt.md) | Bolt CMS 3.7.1 authenticated RCE |
| 06 | [Brooklyn Nine Nine](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/brooklynninenine.md) | FTP, steganography, brute force, GTFOBins |
| 07 | [c4ptur3-th3-fl4g](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/capturetheflag.md) | Encoding, stego, spectrogram, forensics |
| 08 | [Couch](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/couch.md) | CouchDB exposure, Docker API, SSH tunneling |
| 09 | [CTF Collection Vol. 1](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/ctfcollectionvol1.md) | 20 standalone mini-challenges |
| 10 | [Dav](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/dav.md) | WebDAV webshell upload, sudo cat abuse |
| 11 | [Develpy](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/develpy.md) | Python `input()` injection, cron abuse |
| 12 | [Easy Peasy](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/easypeasy.md) | Web enumeration, GOST hashes, cron privesc |
| 13 | [KoTH Food CTF](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/food.md) | Command injection, SUID screen, sudo CVE |
| 14 | [Fowsniff](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/fowsniff.md) | OSINT, MD5 cracking, POP3, writable MOTD |
| 15 | [Ice](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/ice.md) | Icecast CVE-2004-1561, UAC bypass, Mimikatz |
| 16 | [Ignite](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/ignite.md) | Fuel CMS RCE (CVE-2018-16763) |
| 17 | [Jack](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/jack.md) | Swapped ports, layered encodings, SUID strings |
| 18 | [Kenobi](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/kenobi.md) | SMB, ProFTPD mod_copy, NFS, PATH hijack |
| 19 | [Kiba](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/kiba.md) | Kibana prototype pollution, Linux capabilities |
| 20 | [LazyAdmin](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/lazyadmin.md) | SweetRice backup disclosure, sudo Perl |
| 21 | [Lian_Yu](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/lianyu.md) | Base58, PNG header repair, stego, pkexec |
| 22 | [Library](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/library.md) | SSH brute force, sudo script replacement |
| 23 | [Linux PrivEsc](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/linuxprivesc.md) | 10+ privesc vectors in one learning VM |
| 24 | [Madness](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/madness.md) | Header repair, ROT13, SUID screen 4.5.0 |
| 25 | [OhSINT](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/ohsint.md) | Pure OSINT reconnaissance |
| 26 | [Overheard at Breakfast](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/overheardatbreakfast.md) | Discord leak → Gravatar hash → hidden flag |
| 27 | [Overpass](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/overpass.md) | Cookie bypass, SSH key cracking, `/etc/hosts` cron |
| 28 | [Path](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/path.md) | IDOR, upload bypass, UnrealIRCd backdoor |
| 29 | [Pickle Rick](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/picklerick.md) | `robots.txt`, command injection, passwordless sudo |
| 30 | [Room 404](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/room404.md) | Exposed `.git` repository reconstruction |
| 31 | [RootMe](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/rootme.md) | File upload, Python library privesc |
| 32 | [Simple CTF](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/simplectf.md) | CMS Made Simple SQLi, vim sudo |
| 33 | [Smag Grotto](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/smaggrotto.md) | PCAP credentials, cron SSH-key swap |
| 34 | [Source](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/source.md) | Webmin 1.890 backdoor, Perl injection |
| 35 | [Tamper](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/tamper.md) | Custom sqlmap tamper for auth-gated SQLi |
| 36 | [The Brochure](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/thebrochure.md) | Instagram SOCMINT, Base64 fragments |
| 37 | [The Cod Caper](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/thecodcaper.md) | SQLi, GDB ret2win buffer overflow |
| 38 | [Thompson](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/thompson.md) | Tomcat WAR deployment, world-writable cron |
| 39 | [Tony the Tiger](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/tonythetiger.md) | JBoss Java deserialization (CVE-2015-7501) |
| 40 | [Wgel](https://github.com/5h4nnu-dev/CTF-Archive/blob/main/src/writeups/wgel.md) | Exposed SSH key, sudo `wget` privesc |

</details>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=3" width="100%" alt="divider" />

## 🚀 &nbsp;Projects

<table>
<tr>
<td width="33%" valign="top" align="center">

### 🛡 Vulnix
![AI](https://img.shields.io/badge/AI-Powered-00FFAA?style=flat-square)
![Scanner](https://img.shields.io/badge/Vulnerability-Scanner-EF4444?style=flat-square)

AI-powered vulnerability scanner

</td>
<td width="33%" valign="top" align="center">

### 🔍 SecureProbe
![Web](https://img.shields.io/badge/Web-Security-38BDF8?style=flat-square)
![Toolkit](https://img.shields.io/badge/Assessment-Toolkit-A855F7?style=flat-square)

Web security assessment toolkit

</td>
<td width="33%" valign="top" align="center">

### 🤖 Emotional AI
![AI](https://img.shields.io/badge/AI-Personality-F472B6?style=flat-square)
![Emotions](https://img.shields.io/badge/Emotion-Aware-FBBF24?style=flat-square)

AI that understands personality & emotions

</td>
</tr>
<tr>
<td width="33%" valign="top" align="center">

### 🎓 ARIS
![Campus](https://img.shields.io/badge/Campus-Surveillance-14B8A6?style=flat-square)
![AI](https://img.shields.io/badge/AI-System-00FFAA?style=flat-square)

AI campus surveillance system

</td>
<td width="33%" valign="top" align="center">

### 👥 AI Team
![Agents](https://img.shields.io/badge/Autonomous-Agents-A855F7?style=flat-square)
![AI](https://img.shields.io/badge/Multi--Agent-AI-38BDF8?style=flat-square)

Autonomous AI Agents

</td>
<td width="33%" valign="top" align="center">

### 📝 [CTF-Archive](https://github.com/5h4nnu-dev/CTF-Archive)
![React](https://img.shields.io/badge/React-Vite-61DAFB?style=flat-square&logo=react&logoColor=black)
![Rooms](https://img.shields.io/badge/40-Rooms-FBBF24?style=flat-square)

40-room CTF writeup blog — React + Vite

</td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=3" width="100%" alt="divider" />

## ⚔ &nbsp;Cyber Arsenal

<div align="center">

| Skill | Proficiency |
| :--- | :--- |
| 🛰 **Recon** | <img src="https://progress-bar.xyz/100/?title=&width=320&color=00FFAA&suffix=%25" alt="Recon 100%" /> |
| 🌐 **Networking** | <img src="https://progress-bar.xyz/100/?title=&width=320&color=38BDF8&suffix=%25" alt="Networking 100%" /> |
| 🐧 **Linux** | <img src="https://progress-bar.xyz/100/?title=&width=320&color=A855F7&suffix=%25" alt="Linux 100%" /> |
| 🤖 **Artificial Intelligence** | <img src="https://progress-bar.xyz/100/?title=&width=320&color=F472B6&suffix=%25" alt="AI 100%" /> |
| 🐍 **Python** | <img src="https://progress-bar.xyz/83/?title=&width=320&color=FBBF24&suffix=%25" alt="Python 83%" /> |
| 🟦 **TypeScript** | <img src="https://progress-bar.xyz/78/?title=&width=320&color=3178C6&suffix=%25" alt="TypeScript 78%" /> |
| ☁ **Cloud** | <img src="https://progress-bar.xyz/55/?title=&width=320&color=14B8A6&suffix=%25" alt="Cloud 55%" /> |
| 🔬 **Reverse Engineering** | <img src="https://progress-bar.xyz/44/?title=&width=320&color=F97316&suffix=%25" alt="Reverse Engineering 44%" /> |
| 🦠 **Malware Analysis** | <img src="https://progress-bar.xyz/33/?title=&width=320&color=EF4444&suffix=%25" alt="Malware Analysis 33%" /> |

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=3" width="100%" alt="divider" />

## 🎯 &nbsp;Current Mission

<table>
<tr>
<td width="50%" valign="top">

### 📖 Learning

![Malware](https://img.shields.io/badge/Malware_Analysis-EF4444?style=for-the-badge&logo=virustotal&logoColor=white)
![RE](https://img.shields.io/badge/Reverse_Engineering-F97316?style=for-the-badge&logo=ghidra&logoColor=white)
![K8s](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Cloud](https://img.shields.io/badge/Cloud_Security-14B8A6?style=for-the-badge&logo=icloud&logoColor=white)
![Agents](https://img.shields.io/badge/AI_Agents-A855F7?style=for-the-badge&logo=openai&logoColor=white)

</td>
<td width="50%" valign="top">

### 🔨 Building

![Vulnix](https://img.shields.io/badge/Vulnix-00FFAA?style=for-the-badge&logoColor=black)
![SecureProbe](https://img.shields.io/badge/SecureProbe-38BDF8?style=for-the-badge&logoColor=black)
![Emotional AI](https://img.shields.io/badge/Emotional_AI-F472B6?style=for-the-badge&logoColor=black)
![AI Team](https://img.shields.io/badge/AI_Team-FBBF24?style=for-the-badge&logoColor=black)

</td>
</tr>
</table>

<div align="center">

> 🏁 **Goal:** Become a Security Engineer building autonomous AI systems.

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=3" width="100%" alt="divider" />

## 🧰 &nbsp;Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,c,java,bash,ts,js&perline=7" alt="Languages" />
  <br><br>
  <img src="https://skillicons.dev/icons?i=linux,arch,docker,kubernetes,git,github,nginx&perline=7" alt="Tools" />
  <br><br>
  <img src="https://skillicons.dev/icons?i=react,vite,nodejs&perline=3" alt="Web" />
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=3" width="100%" alt="divider" />

## 📈 &nbsp;GitHub Statistics

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=5h4nnu-dev&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" alt="GitHub stats" />
  <img height="170" src="https://github-readme-streak-stats.herokuapp.com/?user=5h4nnu-dev&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</p>

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=5h4nnu-dev&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />
</p>

### 📊 Contribution Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=5h4nnu-dev&theme=tokyo-night&hide_border=true&area=true" width="100%" alt="Contribution graph" />
</p>

### 🏅 Trophy Cabinet

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=5h4nnu-dev&theme=algolia&no-frame=true&column=4" alt="Trophies" />
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=3" width="100%" alt="divider" />

<div align="center">

### 💬 Quote of the day

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&italic=true&size=20&duration=4000&pause=1500&color=38BDF8&center=true&vCenter=true&width=600&lines=%22Hack+to+understand.%22;%22Build+to+protect.%22" alt="Quote" />

<br>

![Profile views](https://komarev.com/ghpvc/?username=5h4nnu-dev&color=00ffaa&style=for-the-badge&label=PROFILE+VIEWS)

Thanks for stopping by. ⭐ the repos if they helped you.

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20,24&height=120&section=footer" width="100%" alt="footer wave" />

</div>
