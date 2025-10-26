🛡️ Basic Vulnerability Scan using ManageEngine Vulnerability Manager Plus
📘 Project Overview

This project was completed as part of the Cyber Security Internship – Task 3.
The objective was to perform a basic vulnerability scan on a personal computer using ManageEngine Vulnerability Manager Plus (VMP) to identify potential security weaknesses and understand system-level risks.

🎯 Objective

To use a free vulnerability scanning tool (ManageEngine VMP) to:

Detect vulnerabilities in the operating system and applications.

Understand the Common Vulnerability Scoring System (CVSS).

Learn about risk assessment and basic remediation techniques.

🧰 Tools and Environment
Component	Details
Tool Used	ManageEngine Vulnerability Manager Plus (Community Edition)
Operating System	Windows 11 Home
Target Scanned	Localhost (127.0.0.1)
Browser Interface	https://localhost:8020
Scan Type	Full System Vulnerability Scan
⚙️ Steps Performed
1️⃣ Installation

Downloaded and installed ManageEngine Vulnerability Manager Plus from the official website.

Launched the local web console via https://localhost:8020.

Logged in as Administrator.

2️⃣ Updating the Vulnerability Database

Clicked on Update Vulnerability DB → Update Now to fetch the latest CVE database.

3️⃣ Adding the Target System

The system was automatically added under Managed Systems as:

LAPTOP-K8XXXXX (Windows 11 Home)


Verified local IP address using ipconfig.

4️⃣ Running the Scan

Navigated to Systems → Scan Systems.

Selected the system and started a Full Scan to detect OS and software vulnerabilities.

5️⃣ Reviewing the Results

Opened Reports → Vulnerability Report.

Observed detailed results including:

Vulnerability name

Severity (Critical/High/Medium/Low)

CVSS score

Recommended remediation or patch update
