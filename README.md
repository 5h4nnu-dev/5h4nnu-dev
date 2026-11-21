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
