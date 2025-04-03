# IAM Access Logs Dashboard

**Interactive Power BI Dashboard for Detecting Risky Login Behavior, User Access Hygiene, and IAM Monitoring**

> "Designed to surface hidden identity risks — from excessive logins to missing MFA — and support real-time visibility into user access posture."

![IAM Access Dashboard Preview](./IAM_Access_Preview.png)

---

## What This Project Solves

Identity threats are one of the **top vectors** in modern cybersecurity, yet many orgs struggle with:
- **Missing visibility** into user login behavior  
- **Delayed detection** of brute-force or anomalous logins  
- **Scattered identity data** across systems

This dashboard provides security and IAM teams with:
- **Excessive login attempt detection**
- **MFA enforcement visibility**
- **User account risk profiling**
- **Locked or inactive account tracking**
- **Access activity patterns** by user, day, and event type

---

## Use Case

- **IAM Hygiene Monitoring** for identifying risky users and weak policies  
- **Brute Force Detection** by tracking excessive or failed login attempts  
- **Access Risk Visibility** to flag missing MFA or dormant accounts  
- **SOC-Driven Identity Investigation** to enrich triage with access context  
- **Interview/Test Lab** to practice IAM detection techniques

---

## Audience

- IAM Engineers  
- IT Security Admins  
- SOC Teams supporting identity investigations  
- GRC Analysts reviewing user access audits  
- Cybersecurity Students studying identity security

---

## Dashboard Preview

| **Metric** | **What It Shows** | **Why It Matters** |
|------------|-------------------|---------------------|
| **Excessive Logins** | Users with high login counts per day | Spot brute force or compromised accounts |
| **Missing MFA Flag** | Accounts missing 2FA or MFA setup | Surface major IAM risk gaps |
| **Locked Accounts** | Accounts with lockout or failed attempts | Track failed logins and lockout behavior |
| **Access Type Breakdown** | Logins by method (SSO, VPN, Local) | Analyze risk by access vector |
| **User Risk Score (Optional)** | Risk level per user | Prioritize investigation workload |
| **Time-Based Access Trends** | Login patterns by hour/day | Spot anomalies or off-hours logins |

---

## Key Skills Demonstrated

- **Power BI:** Slicers, time filters, donut & bar charts, DAX filters  
- **IAM Security:** Access policy evaluation, login trend analysis  
- **Security Monitoring:** Behavior analytics, risk flagging  
- **Visual Analytics:** Storytelling with access data  
- **Communication:** Explaining IAM findings in SOC & audit settings

---

## Core Identity Security Concepts

| **Term** | **Definition** |
|---------|----------------|
| **Excessive Logins** | Volume of logins beyond normal behavior — signals brute force, script abuse, or password spraying |
| **MFA (Multi-Factor Authentication)** | Extra authentication layer (e.g. phone, token) beyond password |
| **Account Lockout** | Security measure after failed logins — may signal an attack |
| **Dormant Accounts** | Unused accounts over time — risky if not disabled |
| **Access Vector** | The method used to log in (e.g. VPN, SSO, SSH) — each has different threat implications |

---

## How to Use It

1. Open the `.pbix` file in Power BI Desktop  
2. Filter by user, access method, or timeframe  
3. Identify:
   - Top login users  
   - Accounts missing MFA  
   - Lockouts or failed attempts  
4. Export user-level IAM reports or simulate alert enrichment for SOC workflows

---

## Expansion Ideas

- Add **GeoIP tagging** to map login location anomalies  
- Tie into **SOAR playbooks** for auto-response on risky accounts  
- Add **threshold logic** for alert generation based on login count  
- Show **login success/failure ratio** for each user  
- Add **AD group filtering** for role-based risk views

---

## Live Demo (Coming Soon)

This dashboard will soon be embedded live via Power BI Web Embed for full interactivity in-browser.

---

## License

MIT — free to use, remix, and build with credit.

---

## Built With Purpose

Built to simulate identity visibility workflows for SOC and IAM teams.  
Shows how security analysts can proactively detect identity threats before compromise.  
Crafted by [Dylan Leonard](https://github.com/dylanleonard-1) — Cybersecurity Engineer & Security Automation Architect.
