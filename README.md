<h1 align="center">Gilberto A. Cedillo Soto</h1>
<h3 align="center">Cybersecurity Analyst in training — SOC Operations · Detection Engineering · Cloud Security</h3>

<p align="center">
  B.S. Cybersecurity, Brigham Young University–Idaho (Class of July 2027) · GPA 3.21<br/>
  F-1 international student · <b>CPT-authorized</b> · Available <b>Winter 2027</b> (Jan–Apr, full-time or part-time) and <b>Summer 2027</b> (Apr–Jul) · Willing to relocate anywhere in the US
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/gilberto-cedillo-a75396133">LinkedIn</a> ·
  <a href="mailto:ced23003@byui.edu">ced23003@byui.edu</a> ·
  <a href="https://tryhackme.com/p/Gilberto00">TryHackMe: Gilberto00</a>
</p>

---

## About me

Cybersecurity senior focused on **Security Operations**: alert triage, SIEM investigation, detection engineering, and security automation. Hands-on across **86 TryHackMe labs** — top 7% globally, 16 badges, including the **SOC Level 2 Analyst badge held by ~0.3% of users** — and IT Service Desk experience triaging, documenting, and escalating incidents at BYU–Idaho (Jun 2025 – Mar 2026).

I build the projects below to turn that lab experience into engineering evidence: real detection rules with tests, hardened cloud infrastructure as code, and incident-response automation — each documented so any reviewer can run it, verify it, and read my design decisions.

## Featured projects

### 🔍 Detection & SOC operations

| Project | What it proves |
|---|---|
| [**soc-detection-engineering-lab**](https://github.com/gilbertocedillo/soc-detection-engineering-lab) | 12 Sigma detection rules (LSASS dumping, Kerberoasting, DCSync, Pass-the-Hash, DNS tunneling) with Splunk SPL + Elastic KQL equivalents, MITRE ATT&CK Navigator coverage, and tests: **all rules fire on attack logs, zero false positives on benign traffic** |
| [**aws-n8n-soc-automation**](https://github.com/gilbertocedillo/aws-n8n-soc-automation) | Hardened AWS EC2 (Terraform, least-privilege IAM/Security Groups) that detects SSH/HTTP/FIM attacks, plus an n8n AI workflow that enriches alerts with VirusTotal, triages with an LLM, **auto-isolates the instance and notifies the team in <5 seconds** |

### 🪪 Identity & cloud security

| Project | What it proves |
|---|---|
| [**active-directory-attack-defense-lab**](https://github.com/gilbertocedillo/active-directory-attack-defense-lab) | A full AD lab built, attacked (BloodHound, Kerberoasting, Pass-the-Hash), detected step-by-step via Windows Event IDs, and hardened (gMSA, admin tiering, LAPS) — with an end-to-end findings report |
| [**aws-cloud-detection-ir**](https://github.com/gilbertocedillo/aws-cloud-detection-ir) | AWS control-plane detection: CloudTrail/Athena queries + a Python analyzer (7 detections, 0 false positives), a vulnerable-vs-secure Terraform pair scanned by a mini-Checkov (**9 findings → 0**), remediation Lambdas, and IR runbooks |
| [**cloud-honeypot-cowrie-mitre**](https://github.com/gilbertocedillo/cloud-honeypot-cowrie-mitre) | Cowrie SSH honeypot on EC2: real attacker sessions enriched with VirusTotal, mapped to MITRE ATT&CK by an AI agent, and malicious IPs auto-blocked via NACL/WAF |

### ⚙️ DevSecOps & AI security

| Project | What it proves |
|---|---|
| [**devsecops-pipeline-n8n-ai**](https://github.com/gilbertocedillo/devsecops-pipeline-n8n-ai) | GitHub Actions pipeline (Semgrep + TruffleHog) where an LLM validates each finding, generates the fix, and opens the remediation PR automatically |
| [**ai-security-gateway-dlp**](https://github.com/gilbertocedillo/ai-security-gateway-dlp) | An LLM security proxy: DLP that redacts PII/API keys before they reach the model, anti-prompt-injection filtering (OWASP LLM01), incident logging, and 11 passing tests |

## Toolbox

- **SIEM & Detection:** Splunk (SPL), Elastic, Sigma, Sysmon, MITRE ATT&CK, Cyber Kill Chain, NIST CSF / SP 800-61
- **Network & Tools:** Wireshark, Snort, Nmap, Semgrep, TruffleHog, Checkov, VirusTotal
- **Cloud & IaC:** AWS (EC2, IAM, Security Groups, Lambda, CloudWatch, CloudTrail, GuardDuty, Athena, S3), Terraform
- **Systems & Scripting:** Windows / Active Directory, Linux, Python, SQL, Bash, PowerShell, Git & GitHub Actions, n8n

## Certifications & training

- Google Cybersecurity Professional Certificate · Google Network Security
- BYU–Idaho certificates: IT Fundamentals, Cloud Computing, Cybersecurity
- Microsoft Cybersecurity Analyst Professional Certificate (Coursera)
- Coursework aligned to Cisco CCNA 200-301 and CompTIA Security+ objectives
- Languages: English (fluent) · Spanish (native)

## Currently

- 🎯 Seeking a **paid cybersecurity internship** for Winter/Summer 2027 (SOC, cloud security, GRC, or IT security)
- 🥷 Practicing on TryHackMe (CTFs and King of the Hill) and in the Trace Labs community
- 📚 Preparing to retake the TCM PSAA and TryHackMe PT1 practical certifications

<p align="center"><i>Every project here includes an interview-defense guide: architecture, design decisions, and honest scope — ask me about any file.</i></p>
