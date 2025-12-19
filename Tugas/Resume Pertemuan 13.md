
# PERTEMUAN 13: ISU ETIKA, KEBIJAKAN, KEAMANAN & TATA KELOLA

## Ringkasan Materi

**Topik Utama:** Mengintegrasikan isu-isu etika, kebijakan, keamanan, dan tata kelola dalam strategi TI organisasi.

### Konsep Kunci

**1. Isu Etika dalam TI**

**A. Privacy & Perlindungan Data Pribadi**
- Organisasi menangani data sensitif: identitas, finansial, kesehatan, perilaku
- Dilema: Maksimalkan value dari data vs. privasi individu
- Rekomendasi: Privacy by design, transparansi, consent eksplisit, right to be forgotten

**B. Hak Kekayaan Intelektual & Software Licensing**
- Tension: Software berlisensi mahal vs. tekanan cost
- Temptation: Gunakan cracked/unlicensed software
- Risiko: Jika ketahuan → reputasi rusak, denda besar
- Rekomendasi: Audit lisensi berkala, use open-source, budget untuk licenses

**C. Transparansi Algoritma & AI Bias**
- Black box AI: Pengguna tidak tahu mengapa keputusan made
- Bias algoritma: Model AI bisa discriminate protected groups
- Contoh: Credit scoring AI yang discriminate perempuan/minorities
- Rekomendasi: Explainability, fairness audit, human in the loop, appeal process

**D. Tanggung Jawab Sosial**
- Inklusi digital: Accessible untuk semua (elderly, disabled, low-literacy)
- Financial literacy: Edukasi pengguna tentang safe digital
- Anti-fraud: Prevent scams & misuse
- Environmental: Sustainability dalam IT operations

**2. Kebijakan TI**

**A. Information Security Policy**
- Scope: Data classification, access control, encryption, password policy
- Incident response: Definition, timeline, escalation, post-incident review
- Third-party risk: Vendor assessment, security audit, SLA requirements

**B. Acceptable Use Policy (AUP)**
- Email usage: Business only, no promotional/offensive content
- Internet usage: No adult content, gambling, file-sharing
- BYOD: Approval required, encryption mandatory, remote wipe capability
- System access: No password sharing, auto-logout, no tailgating

**C. Data Privacy & Protection Policy**
- Legal basis: Consent, contract, legal obligation, legitimate interest
- Data collection: Purpose limitation, minimization, accuracy
- Data subject rights: Access, correction, deletion, portability, objection
- Data breach: Notification timeline (72 hours), transparent communication

**D. Change Management Policy**
- Change categories: Emergency (fast-track), Standard (regular process), Minor (simplified)
- Process: Submit → Review → Approval → Testing → Implementation → Rollback prep
- Change window: Scheduled maintenance windows, user communication
- Documentation: Audit trail, effectiveness review

**3. Keamanan Informasi**

**A. CIA Triad**

| Element | Definition | Implementation |
|---------|-----------|-----------------|
| **Confidentiality** | Data not accessible to unauthorized | Encryption, access control, authentication |
| **Integrity** | Data not modified/corrupted | Data validation, digital signatures, version control |
| **Availability** | System accessible when needed | Redundancy, backup, disaster recovery, 99.99% target |

**B. Ancaman Utama**

1. **Phishing & Social Engineering**
   - Attack: Email yang kelihatan dari legitimate source, fake login page
   - Mitigation: Email security gateway, training, reporting mechanism

2. **Ransomware & Malware**
   - Attack: Encrypted files, system unavailable, business disruption
   - Mitigation: Endpoint security, sandbox analysis, network segmentation, offline backup

3. **Insider Threats**
   - Attack: Malicious/negligent employee steal/damage data
   - Mitigation: Access control, monitoring, training, background check, separation of duties

4. **DDoS (Distributed Denial of Service)**
   - Attack: Massive traffic untuk unavailability
   - Mitigation: DDoS service, rate limiting, redundancy, incident response

5. **Data Breach & Unauthorized Access**
   - Attack: Exploit vulnerabilities, brute force, SQL injection
   - Mitigation: Vulnerability management, patching, WAF, database monitoring

**C. Defense in Depth Strategy**

```
Layer 1: PREVENTIVE CONTROLS
├─ Strong authentication (MFA)
├─ Encryption (at rest & in transit)
├─ Access controls & segregation of duties
└─ Security awareness training

Layer 2: DETECTIVE CONTROLS
├─ Security monitoring & logging
├─ Intrusion detection
├─ Behavior analytics
└─ Regular security audits

Layer 3: CORRECTIVE CONTROLS
├─ Incident response procedures
├─ Data recovery & backup
├─ Post-incident reviews
└─ Continuous improvement
```

**4. Tata Kelola TI (IT Governance)**

**A. Governance Structure**

```
BOARD OF DIRECTORS
        ↓
AUDIT COMMITTEE
        ↓
┌─ IT STEERING COMMITTEE (monthly)
├─ RISK & COMPLIANCE COMMITTEE (quarterly)
├─ PRIVACY/DATA GOVERNANCE COUNCIL (quarterly)
└─ PROJECT MANAGEMENT OFFICE (weekly)
        ↓
CIO / HEAD OF IT
        ↓
├─ IT DEVELOPMENT
├─ IT OPERATIONS
├─ IT SECURITY & COMPLIANCE
└─ IT STRATEGY & PMO
```

**B. Decision Rights & RACI**

| Keputusan | Responsible | Accountable | Consulted | Informed |
|-----------|------------|-----------|-----------|----------|
| Approve IT strategy | CIO | Board/Steering | CFO, COO | All depts |
| Approve new system | CIO+Biz Head | CIO | IT Security | Users |
| Security incident response | IT Security Lead | CIO | HR, Legal | All staff |
| Privacy breach notification | Privacy Officer | CIO+Legal | Compliance | Regulators |

**C. Key Governance Mechanisms**

1. **Portfolio Management** → Idea → Selection → Funding → Execution → Benefits
2. **Project Governance** → Clear decision gates, risk monitoring, quality assurance
3. **Risk Management** → Risk register, assessment, mitigation, monitoring
4. **Performance Management** → KPI definition, measurement, review, improvement
5. **Compliance Management** → Regulatory requirement tracking, audit, remediation

### Key Insights Pertemuan 13

✅ Etika, kebijakan, keamanan, governance adalah interconnected
✅ Policies harus formalized & communicated
✅ Security adalah shared responsibility
✅ Governance must be effective dengan discipline
✅ Incident readiness critical
✅ Integrated approach diperlukan untuk comprehensive protection
