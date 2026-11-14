<p align="center">
  <img src="https://spectrum-guardian.com/images/logo.png" alt="Spectrum Guardian Logo" width="120">
</p>

<h1 align="center">Spectrum Guardian</h1>

<p align="center">
  <strong>Advanced Adversary Simulation & Endpoint Security Testing Toolkit</strong><br>
  <em>Helping defenders understand and test against real-world evasion techniques</em>
</p>

<p align="center">
  <a href="https://spectrum-guardian.com">🌐 Website</a> •
  <a href="https://spectrum-guardian.com/features">📋 Features</a> •
  <a href="https://spectrum-guardian.com/blog">📝 Blog</a> •
  <a href="https://spectrum-guardian.com/faq">❓ FAQ</a>
</p>

---

## ⚠️ Legal Disclaimer

> **This software is provided strictly for authorized security testing, adversary simulation, red team operations, and academic research purposes.**
>
> Users are solely responsible for ensuring compliance with all applicable local, national, and international laws before using this software. Unauthorized use of this tool against systems you do not own or have explicit written permission to test is **illegal** and may result in criminal prosecution.
>
> The developers and contributors of Spectrum Guardian assume **no liability** for misuse. By downloading, installing, or using this software, you agree to use it only in environments where you have lawful authorization.

---

## 📖 About

Spectrum Guardian is a professional-grade **adversary simulation framework** designed for cybersecurity professionals, penetration testers, red teams, and security researchers. It provides a controlled environment to evaluate endpoint protection platforms (EPP) and endpoint detection & response (EDR) solutions against sophisticated evasion techniques commonly employed by advanced persistent threat (APT) groups.

Understanding how threat actors operate is essential for building resilient defenses. Spectrum Guardian enables security teams to:

- **Validate** endpoint security controls against advanced evasion methods
- **Identify** detection gaps before real adversaries exploit them
- **Benchmark** antivirus and EDR solutions in realistic attack scenarios
- **Train** SOC analysts and incident responders with realistic adversary behavior

---

## 🔬 Core Capabilities

### 🛡️ Encryption Engine
Multi-layer encryption pipeline for adversary simulation payloads, enabling security teams to test detection capabilities against obfuscated samples.

| Technique | Purpose |
|-----------|---------|
| AES-256 Symmetric Encryption | Simulates advanced payload encryption used by APT groups |
| RC4 Stream Cipher | Tests detection of stream cipher–obfuscated execution routines |
| XOR Chaining | Evaluates heuristic engine response to variable-entropy data blocks |
| Polymorphic Stub Generation | Assesses signature-based detection resilience against mutating loaders |

### ⚡ Execution & Delivery Testing
Evaluate how endpoint solutions respond to various payload delivery and execution vectors:

- **In-Memory Reflective Loading** — Tests EDR visibility into memory-only execution
- **Script-Based Stagers** (PowerShell, HTA) — Assesses script-layer inspection capabilities
- **Process Injection Techniques** — Validates behavioral detection of code injection patterns

### 🔧 Structural Customization
Tools to test heuristic trust scoring and metadata-based detection:

- **Metadata & Version Info Manipulation** — Tests how AV/EDR weighs PE metadata in trust decisions
- **Certificate & Authenticode Analysis** — Evaluates signature verification bypass scenarios
- **File Binding & Resource Embedding** — Tests static analysis depth of multi-resource binaries

### 🧰 Advanced Red Team Modules
Additional modules for comprehensive adversary simulation engagements:

- **PDF Payload Generator** — Tests document-layer inspection and sandboxing
- **HTA Stager Builder** — Evaluates application trust policies and execution controls
- **UAC Bypass Simulation** — Tests privilege escalation detection capabilities

---

## 📊 Tested Against

Spectrum Guardian has been validated against **23+ leading endpoint security solutions** to ensure realistic adversary simulation coverage, including:

| Vendor | Product | Test Category |
|--------|---------|---------------|
| Microsoft | Windows Defender / Microsoft Defender for Endpoint | Real-Time Protection |
| Kaspersky | Endpoint Security | Behavioral + Heuristic |
| Bitdefender | Total Security | Cloud + Local Analysis |
| ESET | Smart Security / Endpoint Security | Advanced Heuristics |
| McAfee | Total Security | Signature + Behavioral |
| Trend Micro | Maximum Security | Machine Learning Engine |
| Norton | 360 | SONAR Behavioral Protection |
| Avast / AVG | Premium Security | CyberCapture Cloud |
| Malwarebytes | Premium | Exploit & Ransomware Protection |
| And more... | 14+ additional engines | Various detection layers |

> Video demonstrations of detection testing are available in the [Tutorials & Demos](https://spectrum-guardian.com/proofs) section.

---

## 🏗️ Project Structure

```
spectrum-guardian/
├── index.html              # Landing page
├── features.html           # Capabilities overview
├── pricing.html            # Licensing tiers
├── tutorials.html          # Tutorial & video archive
├── proofs.html             # Detection test results
├── malware-analysis.html   # AV engine benchmark analysis
├── faq.html                # Frequently asked questions
├── donate.html             # Support the project
├── blog/                   # Security research articles
│   ├── index.html
│   ├── antivirus-comparison-detection-rates-and-algorithms.html
│   ├── cyber-threats-forecast.html
│   ├── ransomware-threat-guide.html
│   └── ...
├── images/                 # Visual assets
├── style.css               # Stylesheet
├── shared.js               # Shared scripts
├── server.py               # Local development server
├── sitemap.xml             # SEO sitemap
├── robots.txt              # Search engine directives
├── 404.html                # Custom error page
└── README.md               # This file
```

---

## 🚀 Deployment

### Quick Start (Local Preview)
```bash
python server.py
# Open http://localhost:8000 in your browser
```

### Production Hosting
This project is a static website ready for deployment on any standard web host. See [README_DEPLOYMENT.txt](README_DEPLOYMENT.txt) for detailed instructions covering:

- **cPanel / File Manager** upload (recommended)
- **FTP / SFTP** deployment via FileZilla
- SSL/TLS configuration
- Clean URL rewriting via `.htaccess`

---

## 📝 Research Blog

The Spectrum Guardian blog publishes educational articles on:

- 🔍 Antivirus detection algorithms and evasion technique analysis
- 📈 Annual AV benchmark comparisons and detection rate studies
- 🛡️ Ransomware kill-chain breakdowns and defense strategies
- 🌐 Emerging cyber threat landscape forecasts
- 🧪 Technical deep-dives into encryption, obfuscation, and binary analysis

Browse all articles at [spectrum-guardian.com/blog](https://spectrum-guardian.com/blog).

---

## 🎯 Who Is This For?

| Role | Use Case |
|------|----------|
| **Penetration Testers** | Simulating advanced threats during authorized engagements |
| **Red Team Operators** | Testing organizational defenses with realistic TTPs |
| **Security Researchers** | Studying evasion techniques for academic or defensive purposes |
| **SOC / Blue Team** | Understanding adversary tradecraft to improve detection rules |
| **AV/EDR Vendors** | Benchmarking detection engines against novel evasion methods |

---

## 📜 Responsible Use Policy

This project adheres to the principles of **responsible security research**:

1. **Authorization Required** — Only use against systems you own or have explicit written authorization to test.
2. **No Malicious Distribution** — Do not use outputs of this tool to harm individuals, organizations, or infrastructure.
3. **Ethical Disclosure** — Any vulnerabilities discovered during testing should be reported through responsible disclosure channels.
4. **Compliance** — Users must comply with all applicable laws, including but not limited to the Computer Fraud and Abuse Act (CFAA), GDPR, and equivalent legislation in their jurisdiction.
5. **Educational Purpose** — This tool exists to improve the state of cybersecurity defense, not to enable attacks.

---

## 🔒 Security Policy

If you discover a security vulnerability in this project, please report it responsibly:

- **Email:** developer@spectrum-guardian.com
- **Response Time:** We aim to acknowledge reports within 48 hours

Please do **not** open public issues for security vulnerabilities.

---

## 📄 License

This project is proprietary software. All rights reserved.

Unauthorized reproduction, distribution, or modification is prohibited without explicit written consent from the Spectrum Guardian team. See [Pricing](https://spectrum-guardian.com/pricing) for licensing options.

---

## 🤝 Contributing

Contributions to the research blog and documentation are welcome. For security tool improvements or feature requests, please contact us directly through our website.

---

## 📬 Contact

- **Website:** [spectrum-guardian.com](https://spectrum-guardian.com)
- **Support:** Available 24/7 through the website

---

<p align="center">
  <sub>Built for defenders. Engineered for realism. Used responsibly.</sub>
</p>
