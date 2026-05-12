# Zero-Touch-Windows-Provisioning-with-Autopilot-

# Windows Autopilot End-to-End Deployment Lab

This project demonstrates a complete Windows Autopilot provisioning workflow using Microsoft Intune, Entra ID, and Windows 11 virtual machines.  
.

---

## 📌 1. Capture the Hardware Hash

### Run PowerShell as Administrator  
*(Insert screenshot here)*  
`![Screenshot](images/01_powershell_admin.png)`

### Install Autopilot Script  
*(Insert screenshot here)*  
`![Screenshot](images/02_install_script.png)`

### Set Execution Policy  
*(Insert screenshot here)*  
`![Screenshot](images/03_execution_policy.png)`

### Export Hardware Hash  
```powershell
Get-WindowsAutoPilotInfo.ps1 -OutFile E:\autohash.csv
