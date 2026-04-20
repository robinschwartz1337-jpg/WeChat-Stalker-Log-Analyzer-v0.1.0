# WeChat-Stalker-Log-Analyzer-v0.1.0
![License](https://img.shields.io/badge/License-Opencreative_4.0-2A6EDB.svg)
![Python](https://img.shields.io/badge/Python-3.10+-3776AB.svg)
![Docker](https://img.shields.io/badge/Docker-2496ED.svg)
![Ollama](https://img.shields.io/badge/Ollama-Local_AI-FF6F00.svg)
![Security](https://img.shields.io/badge/Security_Scanned-brightgreen.svg)
![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub_Actions-2088FF.svg)
![Platform](https://img.shields.io/badge/Platform-Cross--platform-orange.svg)
![Open Source](https://img.shields.io/badge/Open_Source-Yes-3DA639.svg)

# WeChat Stalker Log Analyzer v0.1.0

**Initial Public Release**

After discovering a **13-year-old WeChat log** filled with stalker activity, I analyzed it, cracked the patterns, and solved the threat. That work earned me the **Opencreative 4.0 license**. Today I’m releasing this tool to the public.

### ✨ Key Features
- Advanced WeChat log parser (XML/JSON)
- Stalker pattern detection (repeated contacts, silent-then-active, location tracking, etc.)
- Fully local AI analysis (Ollama + ChromaDB)
- QR code phishing scanner
- Visual HTML reports with timelines & graphs
- Automatic data anonymization

### 📜 License
**Opencreative 4.0** (based on CC BY 4.0)  
Free to use, modify, extend, and distribute commercially. Just give proper attribution.
## 💛 Support This Project

If you find this tool helpful in protecting your digital safety, you can support ongoing development with a Bitcoin donation.

**Bitcoin (BTC) Address:**  
`bc1qn4wnj85qkw6a7n8pz06qvqmqqaszfflxdysss48`

*Thank you for helping keep this project independent and open-source.*
### 🚀 Quick Start

**pip**
```bash
pip install git+https://github.com/robinschwartz1337-jpg/wechat-stalker-analyzer.git
wechat-analyzer --logfile your_log.xml --ai
