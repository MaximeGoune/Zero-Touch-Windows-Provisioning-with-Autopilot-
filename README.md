# Zero-Touch-Windows-Provisioning-with-Autopilot-

# Windows Autopilot End-to-End Deployment Lab

This project demonstrates a complete Windows Autopilot provisioning workflow using Microsoft Intune, Entra ID, and Windows 11 virtual machines.  
.

---

## 📌 1. Capture the Hardware Hash

### Run PowerShell as Administrator  
<img src="https://imgur.com/jaM2tUM" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

### Install Autopilot Script  
<img src="https://imgur.com/jaM2tUM" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

### Set Execution Policy  
<img src="[https://imgur.com/jaM2tUM]" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

### Export Hardware Hash  
```powershell
Get-WindowsAutoPilotInfo.ps1 -OutFile E:\autohash.csv
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

