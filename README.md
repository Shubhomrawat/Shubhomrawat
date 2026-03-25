<div align="center">

```
┌─────────────────────────────────────────────────────────────────────┐
│                                                                     │
│   [!] UNAUTHORIZED ACCESS DETECTED                                  │
│   [!] INITIATING IDENTITY VERIFICATION PROTOCOL...                 │
│   [!] CHALLENGE MODE: ACTIVE                                        │
│                                                                     │
│   > You have entered a restricted terminal.                         │
│   > Prove you belong here. Find the flag.                           │
│                                                                     │
│       FLAG FORMAT:  flag{??_???_????????}                           │
│       DIFFICULTY:   [ ████████░░ ] MEDIUM                          │
│       HINTS:        3 available (use wisely)                        │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

<img src="https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&size=18&pause=800&color=00FF9C&center=true&vCenter=true&width=750&lines=%5BSYSTEM%5D+Intruder+detected+at+%2Fhome%2Fshubhom;%5BWARN%5D+3+challenges+stand+between+you+and+the+flag;%5BINIT%5D+Loading+CTF+environment...;%5BREADY%5D+Good+luck.+You%27ll+need+it." alt="Typing SVG" />

![](https://komarev.com/ghpvc/?username=Shubhomrawat&label=VISITORS+%5BTRACKED%5D&color=00FF9C&style=flat-square)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shubhom-rawat-45a2b522b/)
[![Instagram](https://img.shields.io/badge/0day.xploit__101-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/0day.xploit_101)

</div>

---

## `[TERMINAL] $ whoami`

```yaml
╔══════════════════════════════════════════════════════╗
║  UID: [REDACTED]   GID: security   SHELL: /bin/zsh  ║
║  HOME: /home/shubhom   TTY: pts/0                   ║
╚══════════════════════════════════════════════════════╝

name        : Shubhom Rawat
role        : Cybersecurity Researcher & Penetration Tester
location    : Pennsylvania State University, USA
degree      : M.S. Cybersecurity Analytics & Operations (2024–2026)
status      : [HUNTING THREATS] [BUILDING DEFENSES] [HIDING FLAGS]

philosophy  : "Break it to understand it. Understand it to defend it."
```

---

## `[MISSION BRIEFING] $ cat mission.txt`

```
┌─────────────────────────────────────────────────────────────────┐
│  OPERATION: IDENTIFY THE OPERATOR                               │
│                                                                 │
│  STAGE 1 → Crack the cipher.        Get the first clue.        │
│  STAGE 2 → Decode the transmission. Get the second clue.       │
│  STAGE 3 → Bypass the final lock.   Claim your flag.           │
│                                                                 │
│  [NOTE] Each stage is LOCKED. Click to attempt entry.          │
│  [NOTE] The flag reveals itself only to the worthy.            │
└─────────────────────────────────────────────────────────────────┘
```

---

## `[STAGE 1] $ ./crack_cipher.sh` 🔐

<details>
<summary><b>[ LOCKED ] ██████████ — Click to attempt Stage 1</b></summary>

<br/>

```
[STAGE 1: CAESAR CIPHER INTERCEPT]
════════════════════════════════════════════════

Intercepted transmission from target system:

  iwt hxztci epbb xh: iwxh

Cipher specs: ROT-4 applied. Shift it back.
Decode the message above to receive CLUE #1.

════════════════════════════════════════════════
```

<details>
<summary><code>[ SUBMIT ANSWER ]</code> — I decoded it. Show me Clue #1.</summary>

<br/>

```
╔═══════════════════════════════════════════════════╗
║  [✓] DECRYPTION SUCCESSFUL                       ║
║  [✓] Answer: "the silent pass is: this"          ║
║                                                   ║
║  CLUE #1 UNLOCKED:                                ║
║  ┌───────────────────────────────────────────┐   ║
║  │                                           │   ║
║  │   First word of the flag = "this"         │   ║
║  │   flag{this_???_????????}                 │   ║
║  │                                           │   ║
║  └───────────────────────────────────────────┘   ║
║                                                   ║
║  [→] Proceed to Stage 2...                       ║
╚═══════════════════════════════════════════════════╝
```

</details>
</details>

---

## `[STAGE 2] $ ./decode_transmission.sh` 📡

<details>
<summary><b>[ LOCKED ] ██████████ — Click to attempt Stage 2</b></summary>

<br/>

```
[STAGE 2: HEX DECODE]
════════════════════════════════════════════════

A packet was intercepted on the wire.
Payload (hex):

  69 73 5F 61 72 65 5F 79 6F 75 5F 72 65 61 64 79

Translate hex → ASCII.
CyberChef, Python, or your brain. Choose wisely.

  python3 -c "print(bytes.fromhex('69735f61 72655f796f755f 7265616479').decode())"

════════════════════════════════════════════════
```

<details>
<summary><code>[ SUBMIT ANSWER ]</code> — I decoded the hex. Show me Clue #2.</summary>

<br/>

```
╔═══════════════════════════════════════════════════╗
║  [✓] HEX DECODE SUCCESSFUL                       ║
║  [✓] Payload: "is_are_you_ready"                 ║
║                                                   ║
║  CLUE #2 UNLOCKED:                                ║
║  ┌───────────────────────────────────────────┐   ║
║  │                                           │   ║
║  │   Second word of the flag = "is"          │   ║
║  │   flag{this_is_??????}                    │   ║
║  │                                           │   ║
║  └───────────────────────────────────────────┘   ║
║                                                   ║
║  [→] One stage remains. Don't slip now.          ║
╚═══════════════════════════════════════════════════╝
```

</details>
</details>

---

## `[STAGE 3 — FINAL] $ ./bypass_final_lock.sh` 🚨

<details>
<summary><b>[ LOCKED ] ██████████ — Click to attempt Stage 3 (FINAL BOSS)</b></summary>

<br/>

```
[STAGE 3: BINARY IDENTITY LOCK]
════════════════════════════════════════════════

Final lock engaged. Binary sequence intercepted:

  01110011 01101000 01110101 01100010
  01101000 01101111 01101101

Convert binary → ASCII.
The decoded word IS the identity of this operator.
It is also the last word of your flag.

════════════════════════════════════════════════
```

<details>
<summary><code>[ SUBMIT ANSWER ]</code> — I have the final word. REVEAL THE FLAG.</summary>

<br/>

```
╔═══════════════════════════════════════════════════════════════╗
║                                                               ║
║   [✓] BINARY DECODED: "shubhom"                              ║
║   [✓] ALL 3 STAGES CLEARED                                   ║
║   [✓] IDENTITY CONFIRMED: SHUBHOM RAWAT                      ║
║                                                               ║
║   ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   ║
║   ░                                                       ░   ║
║   ░   ███████╗██╗      █████╗  ██████╗                    ░   ║
║   ░   ██╔════╝██║     ██╔══██╗██╔════╝                    ░   ║
║   ░   █████╗  ██║     ███████║██║  ███╗                   ░   ║
║   ░   ██╔══╝  ██║     ██╔══██║██║   ██║                   ░   ║
║   ░   ██║     ███████╗██║  ██║╚██████╔╝                   ░   ║
║   ░   ╚═╝     ╚══════╝╚═╝  ╚═╝ ╚═════╝                   ░   ║
║   ░                                                       ░   ║
║   ░  ┌─────────────────────────────────────────────────┐  ░   ║
║   ░  │                                                 │  ░   ║
║   ░  │        flag{this_is_shubhom}                    │  ░   ║
║   ░  │                                                 │  ░   ║
║   ░  └─────────────────────────────────────────────────┘  ░   ║
║   ░                                                       ░   ║
║   ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   ║
║                                                               ║
║   [+] You've met the operator. Now explore the arsenal.      ║
╚═══════════════════════════════════════════════════════════════╝
```

</details>
</details>

---

## `$ ls -la /projects` — Arsenal

<details>
<summary><b>🔬 Malware Analysis Sandbox</b> — <code>[ACTIVE]</code></summary>
<br/>

> Dynamic malware analysis pipeline powered by **Cuckoo Sandbox** + **YARA rules**.

- Detonates suspicious binaries in an isolated VM environment
- Extracts behavioral signatures: network calls, registry changes, file I/O
- Classifies malware families using YARA pattern matching
- Generates automated threat intelligence reports

**Stack:** `Python` `Cuckoo Sandbox` `YARA` `VirtualBox` `Linux`

</details>

<details>
<summary><b>🧠 Malware Detection via Machine Learning</b> — <code>[DEPLOYED]</code></summary>
<br/>

> Network traffic-based malware classifier using ensemble methods.

- Parses live/recorded network flows from pcap files
- Engineers features from packet metadata & behavioral patterns
- Classifies malicious traffic using **Random Forest** & **Decision Trees**

**Stack:** `Python` `Scikit-learn` `Pandas` `Wireshark/pcap` `Matplotlib`

🔗 [View Repository](https://github.com/Shubhomrawat/Malware-Detection-Using-ML)

</details>

<details>
<summary><b>⚡ ThreatLens — Suspicious Login Detection</b> — <code>[IN PROGRESS]</code></summary>
<br/>

> ML-powered anomaly detection for identifying account takeovers in real time.

- Baselines normal user login behavior (time, location, device fingerprint)
- Flags deviations using anomaly detection algorithms
- Real-time alerting pipeline built for SOC integration

**Stack:** `Python` `TensorFlow` `FastAPI` `PostgreSQL` `Docker`

</details>

<details>
<summary><b>🌐 NetInstall — Encrypted Multi-Machine Deployment</b> — <code>[STABLE]</code></summary>
<br/>

> Automated software deployment across distributed machines over encrypted overlay networks.

- Deploys applications to multiple nodes simultaneously via **ZeroTier**
- Removes dependency on physical network access

**Stack:** `Python` `ZeroTier` `Bash` `Linux`

🔗 [View Repository](https://github.com/NetInstall1)

</details>

<details>
<summary><b>💬 ZenVerse — Secure Communications Platform</b> — <code>[STABLE]</code></summary>
<br/>

> Encrypted real-time messaging and collaboration platform.

🔗 [View Repository](https://github.com/Shubhomrawat/ZenVerse)

</details>

---

## `$ nmap --skills Shubhom`

```
PORT        STATE    SERVICE
22/tcp      open     penetration-testing
80/tcp      open     web-app-security
443/tcp     open     malware-analysis
514/tcp     open     siem-log-analysis        [Splunk | ELK]
8080/tcp    open     ml-threat-detection
9000/tcp    open     security-operations
9200/tcp    open     elasticsearch-hunting
```

### Languages & Scripting
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)

### 🔴 Offensive Security
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=portswigger&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logo=metasploit&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-004088?style=flat-square&logoColor=white)
![Hashcat](https://img.shields.io/badge/Hashcat-2D2D2D?style=flat-square&logoColor=00FF9C)
![SQLmap](https://img.shields.io/badge/SQLmap-CC0000?style=flat-square&logoColor=white)
![Hydra](https://img.shields.io/badge/Hydra-CC0000?style=flat-square&logoColor=white)
![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-00549E?style=flat-square&logo=owasp&logoColor=white)
![Gobuster](https://img.shields.io/badge/Gobuster-4B0082?style=flat-square&logoColor=white)
![Aircrack-ng](https://img.shields.io/badge/Aircrack--ng-1A1A2E?style=flat-square&logoColor=00FF9C)

### 🔵 Defensive Security & SOC
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=00FF9C)
![Elastic](https://img.shields.io/badge/ELK_Stack-005571?style=flat-square&logo=elastic&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![YARA](https://img.shields.io/badge/YARA-FF6B35?style=flat-square&logoColor=white)
![Volatility](https://img.shields.io/badge/Volatility-6A0DAD?style=flat-square&logoColor=white)
![Nessus](https://img.shields.io/badge/Nessus-00C176?style=flat-square&logoColor=white)
![Snort](https://img.shields.io/badge/Snort-FF0000?style=flat-square&logoColor=white)

### 🤖 ML / Security AI
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

### Infrastructure & DevSecOps
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## `$ cat /var/log/github-stats`

<div align="center">

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=Shubhomrawat&show_icons=true&theme=chartreuse-dark&include_all_commits=true&count_private=true&border_color=00FF9C&title_color=00FF9C&icon_color=00FF9C"/>
<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Shubhomrawat&layout=compact&langs_count=8&theme=chartreuse-dark&border_color=00FF9C&title_color=00FF9C"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Shubhomrawat&theme=chartreuse-dark&border=00FF9C&ring=00FF9C&fire=FF6B35&currStreakLabel=00FF9C"/>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Shubhomrawat&theme=react-dark&color=00FF9C&line=00FF9C&point=FFFFFF&area=true&border_color=00FF9C"/>

</div>

---

## `$ ./connect.sh`

<div align="center">

| Platform | Handle |
|----------|--------|
| 🔗 LinkedIn | [shubhom-rawat-45a2b522b](https://www.linkedin.com/in/shubhom-rawat-45a2b522b/) |
| 📸 Instagram | [@0day.xploit_101](https://www.instagram.com/0day.xploit_101) |
| 📘 Facebook | [Profile](https://www.facebook.com/share/A8tKsYm5D3DDvP1V/) |

</div>

---

<div align="center">

```
╔══════════════════════════════════════════════════════════════════════╗
║                                                                      ║
║   [+] CTF complete? Drop a ⭐ as proof of pwn.                      ║
║   [+] Want to collab on something? Open an issue or ping me.        ║
║   [>] Security is not a product. It's a process.                    ║
║   [>] flag{this_is_shubhom} — you earned it.                       ║
║                                                                      ║
╚══════════════════════════════════════════════════════════════════════╝
```

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:007CF0,100:00FF9C&height=120&section=footer)

</div>
