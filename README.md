# Save this block as a UTF-8 file to overwrite the README
$content = @'
<!--
  Enhanced Cybersecurity README
  - Matrix-style banner (GIF or local image recommended)
  - Strong skills/tools section with emojis
  - Personal journey narrative
  - CTA for assets (matrix GIF)
-->

<h1 align="center">🟢 Edward Sila — Cybersecurity Enthusiast</h1>

<p align="center">
  <img alt="matrix-rain" src="https://media.giphy.com/media/3o7aD2saalBwwftBIY/giphy.gif" width="720" />
</p>

## About Me

I'm Edward — a curious and persistent cybersecurity enthusiast on a mission to think like attackers so I can better defend systems. I specialize in hands-on offensive security techniques, defensive hardening, and building reliable automation to repeatable security checks.

## My Journey

I started writing scripts to automate boring tasks and quickly realized that the most interesting problems were the ones where systems broke. That curiosity led me into penetration testing, red-team exercises, and blue-team defense. Every vulnerability I find teaches me how systems fail, and every defense I build makes me a better tester.

## Quick Snapshot

- **Location:** Kenya 🇰🇪
- **Focus:** Penetration Testing, Web App Security, Network Security, Cloud Security
- **Approach:** Automate, test, repeat — then write better detection

## Skillset & Tools

- 🐧 **Linux & Bash:** Comfortable with CLI, shell scripting and system internals
- 🧭 **Networking:** TCP/IP, DNS, routing, packet analysis (Wireshark)
- 🛠️ **Core Tools:** `git`, `nmap`, `gobuster`, `burpsuite`, `sqlmap`, `nikto`, `hydra`, `metasploit`
- 🔍 **Recon & Scanning:** `amass`, `sublist3r`, `masscan`, `dirsearch`
- 🔐 **Password & Crypto:** `john`, `hashcat`, credential auditing
- 🧪 **Automation:** Python for tooling and PoCs; Docker for isolated testbeds
- ☁️ **Cloud & Infra:** AWS basics, container security, IaC review

## Projects & Demos

- Offensive playbooks: recon pipelines that combine `amass`, `nmap`, and `gobuster` to discover hosts and directories.
- Burp Suite collections for web app testing and proof-of-concept exploits.
- Custom scripts to parse and triage large scan outputs into actionable findings.

(See `/projects` for labs and PoC code — add or link projects here.)

## What I Carry In My Toolkit

`nmap`, `gobuster`, `dirsearch`, `amass`, `masscan`, `Burp Suite`, `sqlmap`, `Nikto`, `Metasploit`, `Wireshark`, `Hydra`, `John`, `Hashcat`, `OpenVAS`/`Nessus`, `Docker`, `git`, `Python`, `Bash`

## Ethics & Responsible Disclosure

I operate ethically. I only test systems I own or have explicit written permission to test. If you find an issue in my projects or infrastructure, please contact me privately so we can responsibly disclose and remediate.

## Get in Touch

- LinkedIn: https://www.linkedin.com/in/edward-sila-a8a262242/
- GitHub: https://github.com/edwardsila

## Make the README shine (optional)

- For an animated Matrix header, drop a `matrix.gif` into `assets/` and replace the image source above with `/assets/matrix.gif`.
- Want a dark-mode version or badges for certifications? Tell me which certs and I'll add custom shields.

---

<p align="center">
  <a href="https://github.com/edwardsila">
    <img src="https://github-readme-stats.vercel.app/api?username=edwardsila&show_icons=true&locale=en" alt="GitHub Stats" />
  </a>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=edwardsila" alt="GitHub Streak Stats" />
</p>

**Legend:** If you'd like more visual flair (SVG badges, animated banner from a local `matrix.gif`, or GitHub Action that updates stats), tell me what you prefer and I'll wire it up.
'@

Set-Content -Path 'c:\Users\Administrator\Documents\edwardsila\README.md' -Value $content -Encoding UTF8