# PowerShell Basics Cheat Sheet

A quick reference guide for sysadmins to speed up automation with PowerShell.

---

🖥️ Getting Started


Get-Help <cmdlet> -Full      # Show detailed help for a cmdlet
Get-Command *service*        # Find commands with 'service' in the name
Get-Alias                    # List all aliases

📂 Files & Folders

Get-ChildItem                # List files and folders (like 'dir')
New-Item file.txt            # Create a new file
Remove-Item file.txt         # Delete a file
Copy-Item file.txt C:\Temp   # Copy file
Move-Item file.txt C:\Temp   # Move file

👤 Users & Processes

Get-Process                  # List running processes
Stop-Process -Name notepad   # Kill a process
Get-LocalUser                # List local users

🔍 System Information

Get-ComputerInfo             # Show full system info
Get-Service                  # List Windows services
Get-HotFix                   # Installed updates/patches

🌐 Networking

Test-Connection google.com   # Ping
Get-NetIPAddress             # Show IP configuration
Get-NetTCPConnection         # List active connections

📊 Active Directory (requires RSAT/AD module)

Get-ADUser -Filter *         # List all AD users
Get-ADGroup -Filter *        # List all AD groups

📌 Tips

Use Get-Help for learning.

Combine commands with the pipeline |.

Use Export-Csv to save results.
Get-Service | Export-Csv C:\services.csv -NoTypeInformation

