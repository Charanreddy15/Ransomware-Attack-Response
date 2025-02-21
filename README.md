# Ransomware Attack Response Project

## Overview
This project documents a ransomware attack scenario, its delivery methods, impact, and response strategies. It is designed to serve as an educational resource for cybersecurity students and professionals.

## Team Members
- Sukesh Goud Kootikanti  
- Sai Charan Sudireddy  
- Pranitha Gayatri Thangirala  
- Harshitha Thokala  
- Bhavishya Tatineni  

## Incident Summary

### Timeline
- **Day 1:** Security patches are discontinued, increasing vulnerability.
- **Day 2:** Employee reports stolen laptop with sensitive data.
- **Day 4:** DHS alerts about a new ransomware variant.
- **Day 6:** HR employee’s email is compromised, leading to a system admin clicking a malicious link.
- **Day 7:** Intrusion detection logs show unusual traffic.
- **Day 8:** Website suffers unauthorized redirects and modifications.
- **Day 9:** Ransomware attack demands $53,000 in Bitcoin.
- **Day 10:** Dark Web reports sale of sensitive data.
- **Day 11:** Media reaches out for comment on the breach.

## Ransomware Delivery Methods
- Phishing Emails with Malicious Attachments
- Malicious Links
- Exploiting Software Vulnerabilities

## After Effects
- Data Loss
- Financial Damage
- Reputation Damage

## Incident Response Plan

### Preparation
- Implement security patches.
- Conduct regular cybersecurity training.

### Identification & Detection
- Deploy Intrusion Detection Systems (IDS).
- Monitor endpoint protection solutions.
- Analyze logs for anomalies.

### Containment
- Isolate affected systems.
- Shut down vulnerable services.
- Apply security patches.
- Disable compromised accounts.

### Eradication
- Wipe and rebuild infected systems.
- Restore from backups.
- Close vulnerabilities that enabled access.

### Recovery
- Restore clean backups.
- Enforce multi-factor authentication.
- Monitor restored systems.

### Legal & Compliance
- Follow breach disclosure laws.
- Preserve forensic evidence.
- Consult legal teams before paying ransom.

## References
- Almashhadani et al., "A Multi-Classifier Network-Based Crypto Ransomware Detection System: A Case Study of Locky Ransomware," IEEE Access, 2019. [DOI:10.1109/ACCESS.2019.2907485](https://doi.org/10.1109/ACCESS.2019.2907485)
- Aslan & Samet, "A Comprehensive Review on Malware Detection Approaches," IEEE Access, 2020. [DOI:10.1109/ACCESS.2019.2963724](https://doi.org/10.1109/ACCESS.2019.2963724)
- MITRE ATT&CK Ransomware Tactics: <https://attack.mitre.org/tactics/TA0042/>
- CISA Ransomware Guide: <https://www.cisa.gov/ransomware>

## Repository Structure
```
Ransomware-Attack-Response/
│── Presentation/
│   └── ransomware_presentation.pptx
│── docs/
│   ├── research_papers.md
│   └── incident_response_plan.md
│── README.md
│── .gitignore
```

## Contribution
Feel free to fork this repository and submit pull requests for improvements!

## License
This project is for educational purposes only and follows an open-source license.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Ransomware-Attack-Response.git
   cd Ransomware-Attack-Response
   ```

2. Add project files and commit changes:
   ```bash
   git add .
   git commit -m "Initial commit with project files"
   ```

3. Push to GitHub:
   ```bash
   git push origin main
   ```
