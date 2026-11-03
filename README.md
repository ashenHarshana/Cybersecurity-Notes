# Cybersecurity-Notes[README.md](https://github.com/user-attachments/files/34312940/README.md)
<div align="center">

# 🛡️ NB5004CEM · Cybersecurity

### Think like a defender. Model the threats. Justify the controls.

**BSc (Hons) Computing** · Awarded by **Coventry University** · Delivered at **NIBM**

![Level](https://img.shields.io/badge/Level-5-2563eb?style=for-the-badge) ![Credits](https://img.shields.io/badge/Credits-20-7c3aed?style=for-the-badge) ![Sessions](https://img.shields.io/badge/Sessions-12-0891b2?style=for-the-badge) ![Licence](https://img.shields.io/badge/Licence-MIT-16a34a?style=for-the-badge)

**Module Leader:** Niranga Dharmaratna

**13 slide decks** (including the prelude) · **13 interactive demos** · **One integrated coursework**

[📘 Start with the Prelude](https://nirangadh.github.io/NB5004CEM-Cybersecurity/NB5004CEM_Cybersecurity_Prelude.pdf) · [🧭 Browse Sessions](#-session-guide) · [📊 Assessment](#-assessment-at-a-glance) · [🧰 Lab Tools](#-lab-tools)

</div>

---

> [!IMPORTANT]
> **Start here:** Read the [Module Prelude](https://nirangadh.github.io/NB5004CEM-Cybersecurity/NB5004CEM_Cybersecurity_Prelude.pdf) before Session 1. It explains how the module runs, how you are assessed, and what you are expected to produce.

> [!NOTE]
> **Your assigned industry domain matters throughout.** Every session, lab, and coursework section must be grounded in the domain assigned to you. Assignment details are issued in Session 1 and in the coursework brief.

## 📚 Contents

- [Overview](#-overview)
- [How to use this repository](#-how-to-use-this-repository)
- [Session guide](#-session-guide)
- [Quick index](#-quick-index)
- [Assessment at a glance](#-assessment-at-a-glance)
- [Coursework progress roadmap](#-coursework-progress-roadmap)
- [Lab tools](#-lab-tools)
- [Ethical use](#-ethical-use)
- [Troubleshooting](#-troubleshooting)
- [Repository structure](#-repository-structure)
- [Licence and attribution](#-licence-and-attribution)

## 🔎 Overview

This repository contains student resources for **NB5004CEM Cybersecurity**, a Level 5, 20-credit module delivered across **12 sessions**. It brings together the slide decks and the interactive classroom demonstrations, progressing from security properties and threat modelling to testing, compliance, traceability, and viva preparation.

| 🧱 Five security layers | 🔐 Security thinking | 🧪 Hands-on learning |
|---|---|---|
| Data · IAM · Application · Network · System | Properties, risks, requirements, controls, and evidence | Browser-based interactive demos and authorised lab tools |

**Key principle:** The coursework evaluates the **security apparatus of a known existing system**. You are **not** being asked to design or build a new system.

## 🚀 How to use this repository

1. **Read the [Module Prelude](https://nirangadh.github.io/NB5004CEM-Cybersecurity/NB5004CEM_Cybersecurity_Prelude.pdf).** Understand the module and assessment before starting.
2. **Open a session slide deck.** Each PDF can be viewed in the browser or downloaded for offline study.
3. **Try its interactive demo.** The self-contained HTML demos run locally in your browser, require no account or installation, make no network calls, and do not send data off your device.
4. **Apply the learning to your assigned domain.** Each session contributes directly to your coursework submission.
5. **Download the repository if needed.** Select the green **Code** button on GitHub, then **Download ZIP**.

> [!TIP]
> To use a demo offline, download the actual `.html` file and double-click it. The published-page links below also work online.

## 🗺️ Session guide

### 01 · Security Thinking: Properties and Layers

**Focus:** The extended CIA model, five security properties, and the five-layer framework used throughout the module.

**Layers:** All five  
**Coursework output:** A1 context vocabulary and asset identification

- 📑 [Slide deck — 28 slides](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s1/NB5004CEM_S1_SecurityThinking.pdf)
- 🧩 [Demo: Breach to 5-Property Mapper](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s1/NB5004CEM_S1_SecurityThinking_Demo_PropertyMapper.html) — Take a real breach and map which of the five properties failed.

### 02 · Threat Thinking: Actors, STRIDE and Trust Boundaries

**Focus:** Threat actors and motivations, STRIDE, and trust boundaries on architecture diagrams.

**Layers:** All five  
**Coursework output:** A2 architecture diagram, A3 threat model

- 📑 [Slide deck — 26 slides](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s2/NB5004CEM_S2_ThreatThinking.pdf)
- 🧩 [Demo: STRIDE Mapper](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s2/NB5004CEM_S2_ThreatThinking_Demo_STRIDEMapper.html) — Map STRIDE threat categories to the security properties they violate.

### 03 · Cryptography: Properties, Not Mathematics

**Focus:** What hashing, encryption, certificates, and signatures guarantee—and what they do not.

**Layers:** Data, Network, Application  
**Coursework output:** DATA-01, DATA-02, section B5

- 📑 [Slide deck — 26 slides](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s3/NB5004CEM_S3_Cryptography.pdf)
- 🧩 [Demo: Avalanche Hasher and Compare](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s3/NB5004CEM_S3_Cryptography_Demo_AvalancheHasher.html) — Change one character and observe the resulting hash change.

### 04 · Authentication: Passwords and Sessions

**Focus:** Password storage, session handling, cookie flags, token structure, and common authentication failures.

**Layers:** IAM  
**Coursework output:** IAM-01, section B2

- 📑 [Slide deck — 25 slides](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s4/NB5004CEM_S4_Authentication.pdf)
- 🧩 [Demo: Cookie Flag Toggler](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s4/NB5004CEM_S4_Authentication_Demo_CookieToggler.html) — Toggle `Secure`, `HttpOnly`, and `SameSite` to see what each prevents.
- 🧩 [Demo: JWT Anatomy and None-Attack](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s4/NB5004CEM_S4_Authentication_Demo_JWTDecoder.html) — Decode and edit a token to understand why signature verification matters.

### 05 · Authorisation, MFA and Least Privilege

**Focus:** Authentication versus authorisation, role design, privilege escalation, and individual accountability.

**Layers:** IAM  
**Coursework output:** IAM-02, section B2

- 📑 [Slide deck — 28 slides](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s5/NB5004CEM_S5_Authorisation.pdf)
- 🧩 [Demo: Role-Permission Matrix and Escalation Finder](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s5/NB5004CEM_S5_Authorisation_Demo_RoleMatrix.html) — Build a role matrix and identify a hidden escalation path.

### 06 · Application Security: OWASP Top 10

**Focus:** Common and severe application vulnerabilities and the security properties they affect.

**Layers:** Application  
**Coursework output:** APP-01, section B4

- 📑 [Slide deck — 24 slides](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s6/NB5004CEM_S6_OWASP.pdf)
- 🧩 [Demo: Query Structure Sandbox](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s6/NB5004CEM_S6_OWASP_Demo_QueryStructureSandbox.html) — Enter search text and watch the underlying query structure change.

### 07 · Network and System Security

**Focus:** Segmentation, hardening, patching, and shared responsibility across cloud, on-premises, and hybrid environments.

**Layers:** Network, System  
**Coursework output:** NET-01 to NET-03, SYS-01, sections B1 and B3

- 📑 [Slide deck — 24 slides](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s7/NB5004CEM_S7_NetworkSystem.pdf)
- 🧩 [Demo: Shared-Responsibility Slider](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s7/NB5004CEM_S7_NetworkSystem_Demo_SharedResponsibilitySlider.html) — Compare your responsibilities under on-premises, IaaS, PaaS, and SaaS.

### 08 · Methodology, SRS Writing and Shared Responsibility

**Focus:** Writing testable security requirements and describing the target environment for security controls.

**Layers:** All five  
**Coursework output:** A4 mini-SRS draft and B1 target environment draft

- 📑 [Slide deck — 24 slides](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s8/NB5004CEM_S8_SRSWriting.pdf)
- 🧩 [Demo: SRS Testability Validator and CVSS Explorer](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s8/NB5004CEM_S8_SRSWriting_Demo_TestabilityCVSS.html) — Test a draft requirement and see why it may be untestable.

### 09 · Scanning and Interception Tools

**Focus:** Safe and ethical assessment tooling, scan interpretation, passive scanning, and scanner limitations.

**Layers:** Application, Network  
**Coursework output:** Evidence for sections B3 and B4

- 📑 [Slide deck — 24 slides](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s9/NB5004CEM_S9_ScanningTools.pdf)
- 🧩 [Demo: Blind Spot Probe](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s9/NB5004CEM_S9_ScanningTools_Demo_BlindSpotProbe.html) — Explore what automated scanners report and what they miss.

### 10 · Static and Configuration Analysis

**Focus:** Response headers, TLS configuration, transport grading, and security decisions made in configuration.

**Layers:** Application, Network, System  
**Coursework output:** Configuration findings for section B4

- 📑 [Slide deck — 24 slides](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s10/NB5004CEM_S10_StaticConfig.pdf)
- 🧩 [Demo: Security Headers and TLS Grade Explainer](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s10/NB5004CEM_S10_StaticConfig_Demo_HeadersTLSExplainer.html) — Toggle headers and see changes to the grade and attack surface.

### 11 · Observability, Compliance and Resilience

**Focus:** Logging, detection, backups, recovery, and domain-relevant compliance frameworks.

**Layers:** All five  
**Coursework output:** Sections B6, B7 and B8

- 📑 [Slide deck — 26 slides](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s11/NB5004CEM_S11_Observability.pdf)
- 🧩 [Demo: Log-Timeline Reconstructor](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s11/NB5004CEM_S11_Observability_Demo_LogTimeline.html) — Reconstruct an attack timeline from raw log entries.

### 12 · Report Writing, Traceability and Viva Preparation

**Focus:** Building a defensible report, completing requirement-to-control traceability, and preparing for the viva.

**Layers:** All five  
**Coursework output:** Section B9 and viva preparation

- 📑 [Slide deck — 25 slides](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s12/NB5004CEM_S12_ReportingViva.pdf)
- 🧩 [Demo: Finding Grader and Traceability Matrix](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s12/NB5004CEM_S12_ReportingViva_Demo_FindingQualityAndTraceability.html) — Grade a finding against the rubric and build a requirement-to-control chain.

## ⚡ Quick index

| Session | Topic | Slides | Interactive demo |
|:--:|---|:--:|---|
| Prelude | Module structure and assessment | [PDF](https://nirangadh.github.io/NB5004CEM-Cybersecurity/NB5004CEM_Cybersecurity_Prelude.pdf) | — |
| 01 | Security properties and layers | [PDF](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s1/NB5004CEM_S1_SecurityThinking.pdf) | [Property Mapper](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s1/NB5004CEM_S1_SecurityThinking_Demo_PropertyMapper.html) |
| 02 | Threat actors, STRIDE, trust boundaries | [PDF](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s2/NB5004CEM_S2_ThreatThinking.pdf) | [STRIDE Mapper](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s2/NB5004CEM_S2_ThreatThinking_Demo_STRIDEMapper.html) |
| 03 | Cryptography as property guarantees | [PDF](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s3/NB5004CEM_S3_Cryptography.pdf) | [Avalanche Hasher](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s3/NB5004CEM_S3_Cryptography_Demo_AvalancheHasher.html) |
| 04 | Authentication, passwords, sessions | [PDF](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s4/NB5004CEM_S4_Authentication.pdf) | [Cookie Toggler](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s4/NB5004CEM_S4_Authentication_Demo_CookieToggler.html) · [JWT Decoder](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s4/NB5004CEM_S4_Authentication_Demo_JWTDecoder.html) |
| 05 | Authorisation, MFA, least privilege | [PDF](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s5/NB5004CEM_S5_Authorisation.pdf) | [Role Matrix](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s5/NB5004CEM_S5_Authorisation_Demo_RoleMatrix.html) |
| 06 | Application security, OWASP Top 10 | [PDF](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s6/NB5004CEM_S6_OWASP.pdf) | [Query Sandbox](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s6/NB5004CEM_S6_OWASP_Demo_QueryStructureSandbox.html) |
| 07 | Network and system security | [PDF](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s7/NB5004CEM_S7_NetworkSystem.pdf) | [Responsibility Slider](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s7/NB5004CEM_S7_NetworkSystem_Demo_SharedResponsibilitySlider.html) |
| 08 | Methodology and SRS writing | [PDF](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s8/NB5004CEM_S8_SRSWriting.pdf) | [Testability + CVSS](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s8/NB5004CEM_S8_SRSWriting_Demo_TestabilityCVSS.html) |
| 09 | Scanning and interception tools | [PDF](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s9/NB5004CEM_S9_ScanningTools.pdf) | [Blind Spot Probe](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s9/NB5004CEM_S9_ScanningTools_Demo_BlindSpotProbe.html) |
| 10 | Static and configuration analysis | [PDF](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s10/NB5004CEM_S10_StaticConfig.pdf) | [Headers + TLS](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s10/NB5004CEM_S10_StaticConfig_Demo_HeadersTLSExplainer.html) |
| 11 | Observability, compliance, resilience | [PDF](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s11/NB5004CEM_S11_Observability.pdf) | [Log Timeline](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s11/NB5004CEM_S11_Observability_Demo_LogTimeline.html) |
| 12 | Reporting, traceability, viva | [PDF](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s12/NB5004CEM_S12_ReportingViva.pdf) | [Finding Grader](https://nirangadh.github.io/NB5004CEM-Cybersecurity/s12/NB5004CEM_S12_ReportingViva_Demo_FindingQualityAndTraceability.html) |

## 📊 Assessment at a glance

**One coursework · 100 marks · Three components**

```text
Part A       ██████░░░░░░░░░░░░░░  30%
Part B       ████████████░░░░░░░░  60%
Viva Voce   ██░░░░░░░░░░░░░░░░░░  10%
```

| Component | Weight | Requirements |
|---|:---:|---|
| **Part A — System definition and analysis** | **30%** | Context and assets, architecture diagram with trust boundaries, key risks, and mini Security Requirements Specification. **700 words ±10%.** |
| **Part B — Security apparatus** | **60%** | Assumed target environment and the controls, frameworks, and operational design that satisfy the SRS across **B1–B9**. **2,000 words ±10%.** |
| **Viva Voce** | **10%** | **Mandatory 7–10 minute interview** defending your judgements and decisions. **No presentation.** |

> [!WARNING]
> **The coursework brief and evaluation rubric on the LMS are authoritative.** If anything in this README differs from the brief, follow the brief.

## ✅ Coursework progress roadmap

Every session feeds the coursework. Working through each lab should leave you with a nearly complete submission and rehearsed viva answers by Session 12.

| Done | Session | What becomes writable |
|:---:|:---:|---|
| ☐ | 01 | Assets and properties identified; A1 vocabulary |
| ☐ | 02 | Trust boundaries sketched; A3 threat model seeded |
| ☐ | 03 | Cryptographic property choices for Data and Network layers |
| ☐ | 04 | Authentication weaknesses recognised; IAM-01 writable |
| ☐ | 05 | IAM layer complete; all IAM requirements writable |
| ☐ | 06 | Application-layer controls identified |
| ☐ | 07 | All five layers covered; Network and System requirements writable |
| ☐ | 08 | **A4 mini-SRS drafted; B1 target environment drafted** |
| ☐ | 09 | Dynamic tool findings gathered; evidence format established |
| ☐ | 10 | Configuration findings gathered |
| ☐ | 11 | **B6, B7, and B8 writable** |
| ☐ | 12 | **B9 traceability completed; report polished; viva rehearsed** |

## 🧰 Lab tools

Most sessions use free, browser-accessible tools. Some activities require a local installation or a shared VM.

| Session | Tool / resource | Access |
|:---:|---|---|
| 01 | [CVE database](https://www.cve.org/) · [NVD](https://nvd.nist.gov/) | Browser |
| 02 | [MITRE ATT&CK Navigator](https://mitre-attack.github.io/attack-navigator/) | Browser |
| 03 | Browser developer tools | Browser |
| 04 | Browser developer tools; deliberately vulnerable demo app | Browser or shared VM |
| 05 | [DVWA](https://github.com/digininja/DVWA) | Browser or shared VM |
| 06 | [WebGoat](https://owasp.org/www-project-webgoat/) or [DVWA](https://github.com/digininja/DVWA) | Browser or shared VM |
| 07 | [CVE database](https://www.cve.org/); provided architecture diagram | Browser |
| 08 | [NVD CVSS Calculator](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator) | Browser |
| 09 | [OWASP ZAP](https://www.zaproxy.org/); provided demo application | Local install or shared VM |
| 10 | [SecurityHeaders](https://securityheaders.com/) · [SSL Labs](https://www.ssllabs.com/ssltest/) | Browser |
| 11 | Provided log file | Provided artefact; no tools required |
| 12 | Tool output from Sessions 09 and 10 | Previously gathered |

## ⚖️ Ethical use

> [!CAUTION]
> **Scan only systems you are explicitly authorised to scan.** For Sessions 9 and 10, that means the **provided demo application only**. Never scan a real or third-party system without written permission. Unauthorised scanning can constitute a criminal offence, including in Sri Lanka, and breaches NIBM regulations regardless of intent.

All teaching is for **defensive security**: understanding how systems fail so they can be evaluated and improved. The interactive demos in this repository are designed to run locally, make no network requests, and cannot affect anything outside their browser tab.

## 🛠️ Troubleshooting

<details>
<summary><strong>A demo link shows code instead of the demo</strong></summary>

You are probably viewing the raw file on GitHub rather than the published page. Open the published-site links in the [session guide](#-session-guide).

</details>

<details>
<summary><strong>A downloaded demo does not work offline</strong></summary>

Save the `.html` file itself, not a shortcut. Right-click its link, choose **Save Link As**, then double-click the downloaded HTML file.

</details>

<details>
<summary><strong>A PDF will not open in the browser</strong></summary>

Download the PDF and open it in a PDF reader.

</details>

<details>
<summary><strong>Something is missing or a link is broken</strong></summary>

Raise the issue with the module leader.

</details>

## 🗂️ Repository structure

```text
NB5004CEM-Cybersecurity/
├── NB5004CEM_Cybersecurity_Prelude.pdf       # Module prelude
├── s1/                                        # Session 1
│   ├── NB5004CEM_S1_SecurityThinking.pdf
│   └── NB5004CEM_S1_SecurityThinking_Demo_PropertyMapper.html
├── s2/ ... s11/                              # Sessions 2–11
└── s12/                                       # Session 12
    ├── NB5004CEM_S12_ReportingViva.pdf
    └── NB5004CEM_S12_ReportingViva_Demo_FindingQualityAndTraceability.html
```

**Resource totals:** 13 decks (the prelude plus 12 session decks) and 13 demos (one per session, except Session 4, which has two).

## 📄 Licence and attribution

Released under the **MIT Licence**. Free to use, adapt, and share for teaching and learning, with attribution.

Slide content, interactive demos, and module structure by **Niranga Dharmaratna** for **NIBM School of Computing and Engineering**.

Third-party frameworks referenced in the teaching material—including **OWASP**, **MITRE ATT&CK**, **NIST CSF**, and **ISO 27001**—remain the property of their respective owners.

---

<div align="center">

**🛡️ NB5004CEM Cybersecurity**  
NIBM School of Computing and Engineering · Coventry University

*Learn the properties. Understand the threats. Defend the decisions.*

[⬆ Back to top](#️-nb5004cem--cybersecurity)

</div>
