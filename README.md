Sec-Toolkit
Sec-Toolkit is a security tool that provides various security-related functionalities to help protect your systems and networks.

Installation
To install Sec-Toolkit, follow these steps:

Clone this repository
Install the necessary dependencies by running pip install -r requirements.txt
Run the tool using python sec-toolkit.py
Features
Sec-Toolkit provides the following features:

Port scanning and vulnerability assessment
Phishing campaign launcher using Social-Engineer Toolkit (SET)
PowerShell script to gain access to target systems
Results sending to Dradis server
Scan results saving to file
Dependencies
The following dependencies are required for Sec-Toolkit to run:

Python 3.x
nmap
Social-Engineer Toolkit (SET)
PowerShell
Dradis
Usage
To use Sec-Toolkit, run the tool using python sec-toolkit.py. Follow the prompts to select which features to use and enter the necessary information for each task. For example:

markdown
Copy code
python sec-toolkit.py

Select a task:
1. Port scanning and vulnerability assessment
2. Phishing campaign launcher
3. PowerShell script execution
4. Results sending to Dradis server
5. Scan results saving to file

Enter your choice: 1

Enter the target IP address or domain name: 192.168.1.1

Scanning target 192.168.1.1...
Open ports found for target 192.168.1.1: [22, 80]
Vulnerabilities for port 22 (ssh): SSH server CBC mode ciphers enabled
Vulnerabilities for port 80 (http): Apache httpd 2.4.x < 2.4.41 Multiple Vulnerabilities

Scan results saved to file for target 192.168.1.1
Contact
If you have any issues or questions about Sec-Toolkit, please contact us at support@sectoolkit.com.