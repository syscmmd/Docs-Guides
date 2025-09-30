# 10 CMD Tricks Every SysAdmin Should Know

A quick list of useful Command Prompt tricks to make your daily work faster and easier.

---

1. Check your IP configuration

ipconfig /all
Displays full network configuration including DNS and gateways.

2. Test network connectivity

ping google.com
Send ICMP requests to check if a host is reachable.

3. Trace the route to a host

tracert google.com
Shows each hop taken to reach the destination.

4. Display active connections

netstat -an
Lists all TCP and UDP connections with their status.

5. See who is logged into the computer

query user
Displays users currently logged in to the system.

6. Check system uptime

net statistics workstation
Shows system statistics including the last boot time.

7. List all running tasks

tasklist
Lists all processes currently running on the system.

8. Kill a process

taskkill /IM notepad.exe /F
Terminates a process by its name or PID.

9. Check disk usage

chkdsk C:
Displays disk status and file system details.

10. View saved Wi-Fi passwords

netsh wlan show profiles
netsh wlan show profile name="YourWiFi" key=clear
Shows stored Wi-Fi profiles and reveals the saved password.
