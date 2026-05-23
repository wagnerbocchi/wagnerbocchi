<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=200&section=header&text=Wagner%20Bocchi&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=SOC%2FSOAR%20Engineer%20%E2%80%A2%20Ethical%20Hacker%20%E2%80%A2%20Detection%20Engineering&descAlignY=58&descAlign=50&descSize=17" alt="Banner Wagner Bocchi" />
</div>

<div align="center">
  <a href="README.md"><img src="https://img.shields.io/badge/%F0%9F%87%AC%F0%9F%87%A7_English-2C5364?style=for-the-badge" alt="English"></a>
  <a href="README.pt-BR.md"><img src="https://img.shields.io/badge/%F0%9F%87%A7%F0%9F%87%B7_Portugu%C3%AAs-555555?style=for-the-badge" alt="Português"></a>
</div>

<div align="center">
  <a href="https://www.linkedin.com/in/wagner-bocchi" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://wagner.bocchi.company" target="_blank"><img src="https://img.shields.io/badge/Website-000000?style=for-the-badge&logo=githubpages&logoColor=white" alt="Website"></a>
  <a href="https://www.instagram.com/wagnerbocchi/" target="_blank"><img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a>
</div>

---

## 🛡️ About me

Cybersecurity professional working at the frontier between **Red and Blue Team**, focused on **detection, incident response, and automation**. Currently **architecting and implementing a complete SOC/SOAR stack from scratch** — from sizing and installation to detection engineering and automated playbook orchestration.

- 🏗️ Designed a **phased** architecture (all-in-one → distributed multi-node) with HA, DR, and log retention
- 🎯 **Detection Engineering**: Wazuh rule tuning, noise reduction at the source, and MITRE ATT&CK mapping
- 🤖 **SOAR**: automated enrichment and response (Cortex analyzers/responders + Shuffle workflows)
- 🐍 Offensive and defensive automation in **Python** and **Bash**
- 🧠 Neurodivergent — I naturally think in systems, patterns, and attack chains
- 💬 Talk to me about: SIEM/SOAR, threat hunting, pentesting, Linux hardening, detection-as-code

---

## 🔭 The SOC/SOAR stack I'm building

```mermaid
flowchart LR
    EP["🖥️ Endpoints / Servers<br/>(agents + logs)"] -->|events| WZ["🛡️ Wazuh<br/>SIEM / XDR"]
    WZ -->|"alerts (level ≥ 10)"| TH["📋 TheHive 5<br/>Case Management"]
    TH -->|observables| CTX["🔬 Cortex 3<br/>Analyzers / Responders"]
    CTX -->|verdict / IOC| TH
    TH -->|webhook| SH["⚙️ Shuffle<br/>SOAR / Orchestration"]
    SH -->|enrichment| CTX
    SH -->|"containment / response"| EP
    SH -->|notification| NT["🔔 Slack / Email"]

    classDef siem fill:#1E1E2E,stroke:#00B7FF,color:#fff;
    classDef soar fill:#1E1E2E,stroke:#2E8B57,color:#fff;
    class WZ,TH,CTX siem;
    class SH soar;
```

> Detection → triage → enrichment → automated response pipeline. Cloud-hosted with high availability and disaster recovery.

---

## 🎯 Focus areas

<div align="center">

![Offensive Security](https://img.shields.io/badge/Offensive_Security-FF2D2D?style=for-the-badge&logo=hackthebox&logoColor=white)
![Blue Team](https://img.shields.io/badge/Blue_Team-1E90FF?style=for-the-badge&logo=cloudflare&logoColor=white)
![SOC/SOAR](https://img.shields.io/badge/SOC%2FSOAR-6A0DAD?style=for-the-badge&logo=elastic&logoColor=white)
![Detection Eng](https://img.shields.io/badge/Detection_Engineering-00897B?style=for-the-badge&logo=elasticsearch&logoColor=white)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-CF1F2E?style=for-the-badge&logoColor=white)
![OWASP](https://img.shields.io/badge/OWASP-000000?style=for-the-badge&logo=owasp&logoColor=white)

</div>

---

## 🛠️ Stack & Tools

#### 🔐 Security & SecOps
<div>
  <img src="https://img.shields.io/badge/Wazuh-3C7BEF?style=for-the-badge&logoColor=white" alt="Wazuh" />
  <img src="https://img.shields.io/badge/TheHive-FF6F00?style=for-the-badge&logoColor=white" alt="TheHive" />
  <img src="https://img.shields.io/badge/Cortex-1E1E1E?style=for-the-badge&logoColor=white" alt="Cortex" />
  <img src="https://img.shields.io/badge/Shuffle-2E8B57?style=for-the-badge&logoColor=white" alt="Shuffle" />
  <img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white" alt="Burp Suite" />
  <img src="https://img.shields.io/badge/Nmap-4682B4?style=for-the-badge&logo=nmap&logoColor=white" alt="Nmap" />
  <img src="https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white" alt="Metasploit" />
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" alt="Wireshark" />
</div>

#### 💻 Languages
<div>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
</div>

#### ☁️ Infra & Cloud
<div>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white" alt="Arch Linux" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" alt="GCP" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx" />
</div>

#### 🧰 DevOps & Tools
<div>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Neovim-57A143?style=for-the-badge&logo=neovim&logoColor=white" alt="Neovim" />
</div>

---

## 💻 Featured projects

> Focused on **security automation, exploitation, and Red/Blue Team tooling**.

🔐 **[Broken Authentication](https://github.com/wagnerbocchi/broken-authentication)** &nbsp;`Python` &nbsp;·&nbsp; `Offensive`
&nbsp;&nbsp;&nbsp;&nbsp;Suite for identifying authentication flaws in web apps — brute-force, session fixation, and login-flow bypass.

📡 **[PKMID](https://github.com/wagnerbocchi/PKMID)** &nbsp;`Research` &nbsp;·&nbsp; `Networking`
&nbsp;&nbsp;&nbsp;&nbsp;Research on network packet/protocol analysis and manipulation.

🥷 **[h4cker (fork)](https://github.com/wagnerbocchi/h4cker)** &nbsp;`Knowledge Base` &nbsp;·&nbsp; `DFIR`
&nbsp;&nbsp;&nbsp;&nbsp;Curated resources on ethical hacking, bug bounty, and DFIR.

---

## 🏆 Certifications

<table align="center">
  <tr>
    <td align="center" width="200">
      <img src="https://images.credly.com/size/340x340/images/642ec2c6-43e2-4d2a-b2d4-d2f2decfae5d/blob" width="80" alt="Cisco Ethical Hacker" /><br />
      <strong>Ethical Hacker</strong><br />
      <sub>Cisco Networking Academy</sub>
    </td>
  </tr>
</table>

---

## 📊 GitHub Stats

<div align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=wagnerbocchi&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=00B7FF&icon_color=00B7FF&cache_seconds=86400" alt="GitHub Stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=wagnerbocchi&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00B7FF&langs_count=8&cache_seconds=86400" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=wagnerbocchi&theme=tokyonight&hide_border=true&background=0D1117&ring=00B7FF&fire=00B7FF&currStreakLabel=00B7FF" alt="GitHub Streak" />
</div>

---

<div align="center">
  <i>"In a world full of <code>0</code>s and <code>1</code>s, be the <code>exception</code>."</i>
  <br /><br />
  <sub>Thanks for stopping by — feel free to open an <strong>issue</strong>, send a <strong>PR</strong>, or chat about security and tech.</sub>
</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,50:203A43,100:0F2027&height=120&section=footer" alt="footer" />
</div>
