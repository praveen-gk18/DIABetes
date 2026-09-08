# DIABetes
🏛️ DIABetes AI

 One Identity. Zero Typing. 100% On-Device.

A privacy-first AI prototype that auto-fills any Indian government form using DigiLocker, Aadhaar, and bank data — without a single server.
🎯 Problem

1.4 billion Indians manually fill the same 18 data fields across 4,000+ government schemes — spending 20–45 minutes per form, with 15–30% rejection rates due to typos and name mismatches.

💡 Solution

FormBharat reads any government form, fetches verified data from India Stack (DigiLocker + Account Aggregator + Aadhaar eKYC), and auto-fills every field in seconds using on-device AI.

✨ Features

- *5 Government Forms*: NSP Scholarship, Passport, Driving Licence, PAN Card, PM Awas Yojana
- *Auto-Fill Engine*: Typing animation with staggered field completion
- *Mismatch Detection*: Catches name differences between Aadhaar & PAN
- *Eligibility Pre-Check*: Verifies scheme criteria before filling
- *Edge Case Handling*: 12 real-world scenarios (format conversion, expired docs, etc.)
- *Voice Command*: Simulated Hindi voice input
- *100% On-Device*: No server, no cloud, no data leaves the browser

🛠️ Tech Stack

- *Frontend*: Vanilla HTML/CSS/JS (single file, zero dependencies)
- *AI (Production)*: Sarvam 2B via MLC-LLM (on-device)
- *Identity (Production)*: DigiLocker Pull API, Account Aggregator, Aadhaar eKYC
- *Deployment*: Vercel (static site)

 🚀 Run Locally

```bash
 Just open the file in your browser
open index.html
