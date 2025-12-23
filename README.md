

🔐 SOC Incident Report Assistant (L1) - AI Enhanced
<div align="center">
https://img.shields.io/badge/version-v1.0.0-blue
https://img.shields.io/badge/license-MIT-green
https://img.shields.io/badge/AI-Enhanced-purple
https://img.shields.io/badge/SOC-L1%2520Analyst-orange
https://img.shields.io/badge/OpenRouter-API-9cf

Professional incident reporting for Security Operations Centers with AI-powered intelligence

Features • Demo • Installation • Usage • MITRE ATT&CK

</div>
<div align="center"> <img src="https://img.shields.io/badge/-Professional%20SOC%20Reporting-0052CC?style=for-the-badge&logo=github&logoColor=white" /> <img src="https://img.shields.io/badge/-AI%20Powered%20Analysis-7C3AED?style=for-the-badge&logo=openai&logoColor=white" /> <img src="https://img.shields.io/badge/-MITRE%20ATT&CK%20Aligned-C53030?style=for-the-badge&logo=linux&logoColor=white" /> </div>
<p><em>Modern, intuitive interface for SOC analysts</em></p> </div>
🚀 Why This Tool?
Time is critical in incident response. This tool eliminates the 60% of time L1 analysts spend on documentation, allowing them to focus on investigation while generating professional, standardized reports in seconds.

The Problem
❌ Inconsistent report formats across analysts

❌ Manual IOC extraction is time-consuming

❌ MITRE ATT&CK mapping often overlooked

❌ Escalation reports lack critical details

❌ Training new analysts takes weeks

Our Solution
✅ Standardized workflow for all incidents

✅ Auto IOC extraction from evidence

✅ Automatic MITRE mapping by classification

✅ AI-generated escalation reports

✅ Guided interface for new analysts

✨ Features
🤖 AI-Powered Intelligence
Feature	Description	Benefit
Complete Report Generation	AI analyzes evidence and generates professional SOC reports	Saves 15-20 minutes per incident
Automatic IOC Extraction	Extracts IPs, domains, URLs, hashes from evidence	Ensures no IOCs are missed
MITRE ATT&CK Mapping	Maps incidents to relevant techniques automatically	Improves threat intelligence
Missing Detail Detection	Identifies critical information gaps in investigations	Improves report quality
Multi-Model Support	GPT-4, Claude, Gemini, Llama via OpenRouter	Choose the best AI for your needs
🛡️ Professional SOC Workflow
Section	Purpose	Key Elements
Incident Classification	Categorize using MITRE ATT&CK framework	50+ classification options
Evidence Tracking	Document confirmed vs. unconfirmed findings	Chain of custody tracking
Investigation Response	Timeline, containment, eradication steps	Verb-based action tracking
Escalation Decision	Structured escalation reasoning	Risk-based justification
Closure Checklist	Ensure all steps are completed	Compliance verification
🎨 User Experience
Dark/Light Mode Toggle - Comfort for long shifts

Auto-save Functionality - Never lose work

Responsive Design - Works on any device

Copy-to-Clipboard - Easy sharing

Local Storage - No login required

📋 Quick Demo
html
<!-- Simply open in browser and start reporting -->
SOC Incident Report Assistant (L1) - AI Enhanced
├── Classification: Phishing (TA0001)
├── Evidence: [✓] IOC extraction
├── Analysis: [🤖] AI-generated report
└── Output: Professional SOC document
Try it live: Demo Available (Local Host)

🚀 Installation
One-Minute Setup
bash
# 1. Download the tool
git clone https://github.com/EzlikDragon/ndmontederamos-SOC-Incident-Report-Assistant-L1---AI-Enhanced.git

# 2. Navigate to directory
cd soc-report-assistant

# 3. Create API key file (optional)
echo "sk-or-your-api-key-here" > APIkey.txt

# 4. Open in browser
open soc_report_tool_vA.html  # Mac
start soc_report_tool_vA.html  # Windows
xdg-open soc_report_tool_vA.html  # Linux
Requirements
✅ Modern web browser (Chrome 90+, Firefox 88+, Edge 90+)

✅ OpenRouter API key (free tier available)

✅ 5MB disk space

✅ No server, no database, no installation

API Configuration
Get a free API key from OpenRouter

Either:

Place in APIkey.txt (auto-loads)

Enter manually in the tool

Test connection with built-in validator

📖 Usage Guide
1. Incident Triage
javascript
// Example workflow:
1. Select Classification → "Phishing (Spearphishing Link/Attachment)"
2. Choose Endpoint → "Email Gateway / SEG"
3. Set Priority → "Medium"
4. Add Case ID → "ALERT-2024-1223-001"
2. Evidence Collection
javascript
// Add confirmed evidence:
+ Firewall Log: Blocked malicious IP 192.168.1.100
+ Email Header: Suspicious sender spoof@malicious.tld
+ Threat Intel: URL flagged by VirusTotal

// Document gaps:
- Authentication Log: User details pending
- EDR Telemetry: Endpoint scan in progress
3. AI Analysis
javascript
// Click "Generate Complete Incident Report"
1. AI extracts all IOCs automatically
2. Maps to MITRE ATT&CK techniques
3. Generates professional report
4. Suggests containment actions
4. Escalation & Closure
javascript
// For L2/L3 escalation:
✓ Timeline documented
✓ Evidence collected
✓ IOCs extracted
✓ Impact assessed
✓ Justification written
🎯 MITRE ATT&CK Integration
<div align="center">
Tactic	Technique	Example Classification
TA0001	Initial Access	Phishing, Malicious Email
TA0002	Execution	Malware Execution, User Execution
TA0005	Defense Evasion	Obfuscated Files, Signed Binary Abuse
TA0006	Credential Access	Credential Dumping, Brute Force
TA0040	Impact	Ransomware, Data Destruction
</div>
Automatic Mapping:

Classification → MITRE Technique

Evidence → Tactic Grouping

IOCs → Threat Intelligence

Recommendations → Mitigation Steps

🏗️ Architecture

















Technology Stack
Frontend: HTML5, CSS3, Vanilla JavaScript

UI Framework: Bootstrap 5.3

AI Integration: OpenRouter API

Storage: Browser LocalStorage

No Dependencies: Runs completely client-side

📊 Sample Output
text
===============================================================================
INCIDENT REPORT - FOR ESCALATION
===============================================================================
Case ID:           ALERT-2024-1223-001
Status:            UNDER INVESTIGATION
Priority:          High
Classification:    Phishing (Spearphishing Link/Attachment) - T1566.002
Detection Source:  Email Gateway / SEG
Date Created:      2024-12-23T11:20:00
Analyst:           Nicole Dominique Montederamos (L1 Analyst)

===============================================================================
EXECUTIVE SUMMARY
===============================================================================
Malicious phishing email delivered to user inbox containing C2 download link.
Firewall logs show successful outbound connection attempt. Immediate containment
required. MITRE ATT&CK: T1566.002 (Spearphishing Link).

===============================================================================
INDICATORS OF COMPROMISE (IOCs)
===============================================================================
• IP Addresses: 192.168.1.100, 10.0.0.15
• Domains: malicious-c2.tld, phishing-domain.tld
• URLs: https://malicious-c2.tld/download/shell.exe
• File Hashes: a1b2c3d4... (SHA256)
• Email Addresses: spoof@malicious.tld

===============================================================================
[Full professional report continues...]
🔧 Configuration
Customization Options
javascript
// In the HTML file, you can modify:
const CUSTOM_SETTINGS = {
  organizationName: "Your SOC Team",
  defaultAnalyst: "L1 Analyst",
  classificationOptions: [...], // Add custom classifications
  escalationContacts: [...],    // Add team contacts
  customTemplates: {...}        // Modify report format
};
API Model Selection
javascript
// Available models (via OpenRouter):
- openai/gpt-3.5-turbo      // Fast & cost-effective
- openai/gpt-4              // Highest accuracy
- anthropic/claude-3-haiku  // Fast Claude model
- google/gemini-pro         // Google's best
- meta-llama/llama-3.1-8b   // Open source option
🤝 Contributing
We welcome contributions from security professionals!

How to Contribute
Fork the repository

Create a feature branch (git checkout -b feature/improvement)

Commit changes (git commit -m 'Add: New classification type')

Push to branch (git push origin feature/improvement)

Open a Pull Request

Areas for Contribution
📚 Additional classification types

🔌 Integration templates for popular SIEMs

🌐 Translation/localization

🧪 Test cases and validation

📊 Analytics and reporting enhancements

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

text
MIT License

Copyright (c) 2024 SOC Report Assistant Contributors

Permission is hereby granted... [see full license]
Commercial Use: ✅ Allowed
Modifications: ✅ Allowed
Distribution: ✅ Allowed
Private Use: ✅ Allowed
Liability: 🚫 Limited
Warranty: 🚫 None

⚠️ Disclaimer
Important: This tool is designed to assist SOC analysts, not replace professional judgment.

Security Notice
Always verify AI-generated content

Follow organizational incident response procedures

This tool does not perform actual security monitoring

API usage may incur costs (check OpenRouter pricing)

Compliance
Ensure usage complies with your organization's policies

Protect sensitive incident data appropriately

Review AI-generated reports before escalation

Maintain chain of custody for evidence

🌟 Acknowledgments
Built With
Bootstrap 5 - Frontend framework

OpenRouter - AI API gateway

MITRE ATT&CK - Framework

Font Awesome - Icons

Inspired By
Real-world SOC workflows

NIST Cybersecurity Framework

Industry incident response standards

Feedback from L1/L2/L3 analysts

<div align="center">
📞 Support & Community
Having issues or questions?

📖 Check the FAQ (Coming Soon)

🐛 Open an Issue

💬 Join Discussion (Coming Soon)

📧 Email: nd.montederamos@gmail.com

Start Reporting Like a Pro Today
bash
# Clone and begin in under 60 seconds
git clone https://github.com/EzlikDragon/ndmontederamos-SOC-Incident-Report-Assistant-L1---AI-Enhanced.git
Empower your SOC team with AI-enhanced incident reporting 🚀

⬆ Back to Top

</div>
