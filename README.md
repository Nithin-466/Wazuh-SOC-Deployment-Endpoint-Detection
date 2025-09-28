# Wazuh-SOC-Deployment-Endpoint-Detection

This project demonstrates a complete **Security Operations Center (SOC) deployment** using **Wazuh**.   It focuses on **endpoint monitoring**, **file integrity monitoring (FIM)**, and **malware detection and removal** using the **VirusTotal API**.

---

## Project Overview

- **Objective:** Deploy a SOC to monitor Windows endpoints and provide real-time alerts.  
- **Key Features:**  
  - Wazuh Manager & Agent deployment  
  - File Integrity Monitoring (FIM) for Desktop and Downloads  
  - Malware detection and automatic removal using VirusTotal API  
  - Dashboard visualization and alert monitoring  

- **Tools Used:**  
  - Wazuh (SIEM & EDR)  
  - VirtualBox (for Windows VMs)  
  - Windows 7 & 10 endpoints  
  - Python & PyInstaller (for active response script)  
  - VirusTotal API  

---

## Report

The detailed project report is included in the repository as a PDF.  
It contains step-by-step explanations, screenshots, and configurations for the full project.

---

## Screenshots

Below are the screenshots demonstrating the project steps:

<img width="1914" height="963" alt="Screenshot 2025-09-27 175515" src="https://github.com/user-attachments/assets/3bfa3ad3-ea58-4171-8e58-1683277677e7" />
<img width="1919" height="963" alt="Screenshot 2025-09-27 175821" src="https://github.com/user-attachments/assets/138d9510-442b-4ade-8320-d5ad633b8ba9" />
<img width="1812" height="956" alt="Screenshot 2025-09-27 184808" src="https://github.com/user-attachments/assets/191afab1-d793-4dae-a6a6-6c0217bc8650" />
<img width="1896" height="907" alt="Screenshot 2025-09-27 190057" src="https://github.com/user-attachments/assets/f6e4260e-0a4e-4d21-83dc-5d0d3c263b20" />
<img width="1912" height="957" alt="Screenshot 2025-09-27 200437" src="https://github.com/user-attachments/assets/0d4cef23-b2fd-46ba-a22d-ea039c7899f6" />
<img width="1518" height="645" alt="Screenshot 2025-09-27 201006" src="https://github.com/user-attachments/assets/effdf783-ed1c-44cb-84bc-bbf0679486f5" />
<img width="1472" height="986" alt="Screenshot 2025-09-27 201551" src="https://github.com/user-attachments/assets/507f24d5-66ca-4bae-b4c0-7f56b79e399a" />
<img width="1821" height="975" alt="Screenshot 2025-09-27 205356" src="https://github.com/user-attachments/assets/d4978e26-1274-4bfb-b9d7-74007a2b94ca" />
<img width="1912" height="1004" alt="Screenshot 2025-09-27 210440" src="https://github.com/user-attachments/assets/da1114e3-fb50-4c87-8057-2e5c6609b759" />
<img width="1918" height="996" alt="Screenshot 2025-09-27 210709" src="https://github.com/user-attachments/assets/55464a92-bff5-4222-8839-350a701ded45" />
<img width="1890" height="1002" alt="Screenshot 2025-09-27 210821" src="https://github.com/user-attachments/assets/f15ca2e8-6153-4827-9758-8a916bfd7a79" />
<img width="1913" height="1001" alt="Screenshot 2025-09-27 213921" src="https://github.com/user-attachments/assets/b62b0ca8-ffed-4c07-8dbb-e6b9533c326c" />


---

## Active Response Script

The project uses an **active response script** to remove malicious files on Windows endpoints.  

- Script: `remove-threat.py`  
- Converts to executable using **PyInstaller**  
- Monitors the Downloads folder and deletes detected threats automatically

---

## Getting Started

To replicate this project:  

1. Set up **VirtualBox** with Wazuh Manager OVA and Windows endpoints  
2. Deploy Wazuh Agents on Windows systems  
3. Configure File Integrity Monitoring (FIM) for Desktop and Downloads  
4. Set up the active response script for malware removal  
5. Monitor logs and alerts through the Wazuh dashboard  

*Detailed steps are included in the report PDF.*

---

## References

- Wazuh Documentation  
- VirusTotal API  

---

## Author

Nithin – Cybersecurity Enthusiast

LinkedIn: https://www.linkedin.com/in/suddala-nithin-945691356/
