# Northbridge Logistics: 12-Month Security Awareness Program — Task 1: Assess

**Course:** GRC206 · Security Awareness & Training Programs  
**Institution:** International Cybersecurity and Digital Forensics Academy (ICDFA) — School of Cyber Risk, Governance and Compliance  

## Student & Assignment Details

| Field | Details |
| :--- | :--- |
| **Student** | Ibrahim Abdullahi |
| **Registration Number** | 2025/GCR/12720 |
| **Official Email** | gcr2512720@students.icdfa.edu.ng |
| **Program** | GRC Engineering (CGRCE) |
| **Cohort / Session** | Batch B2025 · 2026 Academic Session (Level 1 / Year 1) |
| **Assignment** | Northbridge Logistics: 12-Month Security Awareness Program |

---

## Overview & Planning Assumptions

This document details **Task 1 (Assess)** of a 12-month security awareness and training program for **Northbridge Logistics**, structured in accordance with the lifecycle approach in **NIST SP 800-50r1** (Merritt et al., 2024).

> **Note:** Facts taken directly from the assignment brief are marked **(S)**. All other figures, headcounts, and targets are planning assumptions **(A1–A6)** or illustrative proposals rather than live Northbridge results.

* **A1 — Workforce Segments (Total: 800 (S)):** Finance, procurement, and payroll (35); executives and assistants (25); office-based staff including IT (215); remote sales (100); warehouse supervisors (45); warehouse operatives (380).
* **A2 — Systems:** Corporate email supports a one-click report button, MFA, and simulations; operatives mostly use shared handhelds and have little or no desk time.
* **A3 — Team:** Security Manager plus two analysts (the brief says "small" **(S)**); HR/L&D partner at 0.2 FTE; about 20 volunteer champions at roughly 2 hours a month.
* **A4 — Budget:** About USD 30,000 for the year for tools, printing, translation, and recognition, excluding salaries (the brief says "modest" **(S)**).
* **A5 — Authority:** The sponsor can release 10 paid minutes per shift per month; HR and Legal approve simulations and the staff notice.
* **A6 — Languages and Law:** English plus at least one local language on site; no jurisdiction is stated, so applicable data-protection law is assumed to apply to the regulated customer data **(S)**.

---

## Task 1: Assess

### 1.1 Top Three Human-Driven Risks

The ranking weighs scenario evidence, the potential impact on money and regulated data, and how directly behaviour can change the outcome. Mishandling customer data (for example, misdirected email or unapproved AI tools) was considered and is covered as a topic for office and remote audiences under R2 and R3 rather than as a fourth risk.

| Risk | Scenario Evidence | Why It Ranks High | Unsafe Behaviour $\rightarrow$ Safer Action |
| :--- | :--- | :--- | :--- |
| **R1: Invoice fraud and payment redirection** | Recent invoice-fraud attempts **(S)**. | Direct financial loss. Business email compromise produced 24,768 complaints and about USD 3.05 billion in reported losses to the FBI in 2025 (FBI IC3, 2026). | Pays, or changes bank details, on an emailed or phoned request $\rightarrow$ Verifies by calling a known number and uses two-person approval. |
| **R2: Password reuse and weak credential hygiene** | Two staff reused passwords after a breach **(S)**. Regulated customer data **(S)**. | One reused password turns a single breach into many. Credential abuse appeared in about 39% of breaches in 2025 (Verizon, 2026). | Reuses passwords or shares logins on shared devices $\rightarrow$ Uses unique passwords in an approved manager with MFA and reports suspected exposure at once. |
| **R3: Social engineering across email, SMS and phone, and delayed reporting** | Staff in three work settings, including remote sales **(S)**. | The human element was involved in 62% of breaches (Verizon, 2026). Silence turns a small mistake into an incident, and click-focused training alone changed little in a 19,500-employee trial (Ho et al., 2025). | Ignores, deletes, or hides a suspicious message or their own mistake $\rightarrow$ Reports within minutes through one simple route, without blame. |

### 1.2 Audiences and Their Needs

| Audience (Assumed Size, A1) | Work Context and Needs | Priority Topics (Risk) |
| :--- | :--- | :--- |
| **Finance, procurement and payroll (35)** | Handle invoices, bank-detail changes, and urgent requests; need quick, practical verification steps and the authority to say no. | Verify-before-pay; vendor and executive impersonation; reporting attempts **(R1, R3)** |
| **Executives and assistants (25)** | Frequent impersonation targets who approve payments and set the tone; very little time. | Urgent-request discipline; voice and email impersonation; visible no-blame stance **(R1, R3)** |
| **Office-based staff incl. IT (215)** | Daily email and cloud tools; access to regulated customer data; some desk time. | Phishing and reporting; passwords, MFA, and password manager; safe data handling **(R2, R3)** |
| **Remote sales (100)** | Work off-site on mobiles and public networks; handle customer data; isolated from colleagues; exposed to SMS and phone approaches. | Smishing and vishing; MFA prompts; device and Wi-Fi safety; reporting **(R2, R3)** |
| **Warehouse supervisors (45)** | Lead shifts and are the first contact for operatives; limited desk time. | Running toolbox talks; receiving and escalating reports; shared-login rules **(R2, R3)** |
| **Warehouse operatives (380)** | Shift work on shared handhelds; little desk time; varied language and reading preferences; may receive suspicious calls or texts. | Short practical routines: no shared logins, spot suspicious calls and texts, know how to report **(R2, R3)** |

### 1.3 Pre-Launch Baseline (Months 1–2)

* **Fraud (R1):** 12-month log of invoice-fraud attempts and near misses (how many, how detected, how many reported, any loss). *Sources:* accounts payable records, email gateway logs, incident register.
* **Credentials (R2):** Share of accounts with MFA; number of accounts with breached or reused passwords found by screening against known breach data; password-manager adoption. *Sources:* identity-provider and IT admin reports.
* **Reporting (R3):** One low-difficulty baseline phishing simulation for office and remote staff, recording report rate and time-to-report. Click rate is recorded but treated as secondary (Ho et al., 2025).
* **Culture and Knowledge:** Anonymous 8-question pulse survey (paper or QR code for warehouse): do you know how to report, would you report a mistake without fear, how confident are you spotting fraud.
* **Incident History and Context:** Human-error incidents and time-to-report over the last 12 months (incident register, service-desk tickets); observation of two shift starts and interviews with four supervisors to learn real constraints on time, devices, and language.

---

## References (Task 1)
* Federal Bureau of Investigation, Internet Crime Complaint Center. (2026). *2025 Internet crime report*. https://www.ic3.gov/
* Ho, G., Mirian, A., Luo, E., Tong, K., Lee, E., Liu, L., Longhurst, C. A., Dameff, C., Savage, S., & Voelker, G. M. (2025). Understanding the efficacy of phishing training in practice. *2025 IEEE Symposium on Security and Privacy*. Summary: https://today.ucsd.edu/story/cybersecurity-training-programs-dont-prevent-employees-from-falling-for-phishing-scams
* Merritt, M., Hansche, S., Ellis, B., Sanchez-Cherry, K., Snyder, J. N., & Walden, D. (2024). *Building a cybersecurity and privacy learning program* (NIST Special Publication 800-50r1). National Institute of Standards and Technology. https://doi.org/10.6028/NIST.SP.800-50r1
* Verizon. (2026). *2026 data breach investigations report*. https://www.verizon.com/business/resources/reports/dbir/