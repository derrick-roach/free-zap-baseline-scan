# 🆓 free-zap-baseline-scan ⚡️

A GitHub-powered (Actions & Issues) passive security testing tool using [ZAP baseline scan](https://github.com/zaproxy/action-baseline) to quickly identify misconfigurations and vulnerabilities in web applications.

## 🧪 WIP
This experiment is still a work in progress. 

## 📝 Overview
This project provides an automated GitHub Actions workflow that leverages [ZAP (Zed Attack Proxy)](https://www.zaproxy.org/) to perform passive security scans on web applications. By simply creating a *ZAP Scan Request* issue in this repository with your target URL, you can get detailed security reports - completely free and without setting up any infrastructure.

## 🚀 Benefits & Value
- 🏎️ **FAST** - Only takes 2-3 minutes
- ✅ **EASY** - Just submit a *ZAP Scan Request* issue 
- 🥽 **SAFE** - Passive scan does not attack or harm target website
- 🆓 **FREE** - No cost to you for this lean and efficient security scan
- 🌎 **OPEN** - Publicly accessible to anyone with a GitHub account to try
- ❎ **SETUP** - No installation or integration means no setup and upkeep for you

## ⚡️ Quick Start
### Basic Usage
1️⃣ Open a *ZAP Scan Request* issue to begin.

2️⃣ Results will be posted as a comment on the issue. 

3️⃣ It should only take 2-3 minutes to complete the scan.

4️⃣ Simply check the issue comments in a few minutes for the results.

⚠️ Please ensure that the URL is valid and accessible. Invalid URLs may result in failed scans.

## How It Works
When you submit a *ZAP Scan Request* issue with the correct title, label, and URL, the GitHub Actions workflow automatically:
- Detects and extracts the URL from your issue
- Runs a ZAP baseline scan against the provided URL
- Posts a scan summary and links to the full scan artifacts as a comment on your issue

## Understanding the Results
The scan results include:
- **Alert Summary**: Quick overview of alerts by risk level.
- **Findings List**: Specific issues detected during scanning.
- **Download Links**: Access to full report files for deeper analysis. 
- **Detailed Reports**: HTML, Markdown, and JSON reports available as downloadable artifacts.
- **Recommendations**: Actionable suggestions listed in reports to address identified vulnerabilities.

## Limitations
- It is intended for preliminary security checks and should not replace comprehensive security testing.
- Only performs a baseline scan (passive analysis), which is quick but not exhaustive.
- URLs must be publicly accessible from GitHub's infrastructure.
- Limited to public-facing websites and web applications.
- Does not perform authenticated testing. 

## Privacy & Usage Guidelines
- Scan results are not stored long-term (reports are available as artifacts for limited time)
- This tool is provided for educational, development, and testing purposes 
- Scan data is subject to GitHub's data retention policies

## Contributing
1. Fork this repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add your feature'`).
4. Push your branch (`git push origin feature/your-feature-name`).
5. Open a Pull Request.

## License
This project is licensed under the Apache License. See [LICENSE](LICENSE) for details.

## Acknowledgments
- ZAP Team for their amazing security resources and tools
- GitHub Actions for enabling this automation

## ⚠️ Disclaimer
**Important**: This tool is intended for security testing and education. The maintainers are not responsible for misuse or unauthorized scanning activities.

