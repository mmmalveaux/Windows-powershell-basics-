# Windows PowerShell Basic Commands Lab

This project shows how I used Windows PowerShell to view network information inside a Windows Server virtual machine. I ran commands like `dir` and `Get-NetIPAddress` and documented the output.

## What I Did
- Opened Windows PowerShell as Administrator  
- Listed directory contents using `dir`  
- Displayed all IP information using:

```powershell
Get-NetIPAddress
Get-NetIPAddress -AddressFamily IPv4
