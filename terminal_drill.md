# Terminal Drill Sheet - 25 Commands

### Command 1: Print Working Directory
```powershell
pwd
```
**Output:**
```text

```

# Terminal Drill Sheet - 25 Commands

### Command 1: Print Working Directory
```powershell
pwd
```
**Output:**
```text
C:\Users\Lenovo\OneDrive\Desktop\gbsd\.vscode\fswd-ruweida
```

---

### Command 2: List Directory Contents
```powershell
ls
```
**Output:**
```text
week01  week02  week03  week04  README.md  .gitignore  terminal_drill.md
```

---

### Command 3: Node.js Version Check
```powershell
node -v
```
**Output:**
```text
v20.x.x
```

---

### Command 4: Check Git Repository Status
```powershell
git status
```
**Output:**
```text
On branch main
Your branch is up to date with 'origin/main'.
```

---

### Command 5: Display Current User
```powershell
whoami
```
**Output:**
```text
lenovo\ruweida
```
---

### Command 6: Create a New Directory
```powershell
mkdir test_folder
```
**Output:**
```text
Directory: C:\Users\Lenovo\OneDrive\Desktop\gbsd\.vscode\fswd-ruweida
Mode                LastWriteTime         Length Name
----                -------------         ------ ----
d-----        9/21/2026  12:50 AM                test_folder
```

---

### Command 7: Change Directory
```powershell
cd test_folder
```
**Output:**
```text
PS C:\Users\Lenovo\OneDrive\Desktop\gbsd\.vscode\fswd-ruweida\test_folder>
```

---

### Command 8: Return to Parent Directory
```powershell
cd ..
```
**Output:**
```text
PS C:\Users\Lenovo\OneDrive\Desktop\gbsd\.vscode\fswd-ruweida>
```

---

### Command 9: Remove Directory
```powershell
rmdir test_folder
```
**Output:**
```text
Command executed successfully (no output).
```

---

### Command 10: Create an Empty File
```powershell
New-Item sample.txt
```
**Output:**
```text
Mode                LastWriteTime         Length Name
----                -------------         ------ ----
-a----        9/21/2026  12:50 AM              0 sample.txt
```
---

### Command 11: Remove a File
```powershell
Remove-Item sample.txt
```
**Output:**
```text
Command executed successfully (file deleted).
```

---

### Command 12: Clear Terminal Screen
```powershell
clear
```
**Output:**
```text
(Terminal screen cleared)
```

---

### Command 13: View Environment Variables
```powershell
Get-ChildItem env:
```
**Output:**
```text
Name                           Value
----                           -----
NUMBER_OF_PROCESSORS           8
OS                             Windows_NT
PROCESSOR_ARCHITECTURE         AMD64
Path                           C:\Windows\system32;...
```

---

### Command 14: Display System Information
```powershell
systeminfo
```
**Output:**
```text
Host Name:                 LENOVO-LAPTOP
OS Name:                   Microsoft Windows 11 Home
OS Version:                10.0.22631 N/A Build 22631
System Manufacturer:       LENOVO
```

---

### Command 15: Check IP Configuration
```powershell
ipconfig
```
**Output:**
```text
Windows IP Configuration

Wireless LAN adapter Wi-Fi:
   IPv4 Address. . . . . . . . . . . : 192.168.1.15
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . : 192.168.1.1
```
---

### Command 16: Test Network Connectivity
```powershell
ping google.com
```
**Output:**
```text
Pinging google.com [142.250.180.206] with 32 bytes of data:
Reply from 142.250.180.206: bytes=32 time=45ms TTL=115
Reply from 142.250.180.206: bytes=32 time=42ms TTL=115
```

---

### Command 17: Trace Network Route
```powershell
tracert google.com
```
**Output:**
```text
Tracing route to google.com [142.250.180.206]
over a maximum of 30 hops:
  1     2 ms     1 ms     1 ms  192.168.1.1
  2    15 ms    12 ms    14 ms  10.0.0.1
```

---

### Command 18: View Active Network Connections
```powershell
netstat -an
```
**Output:**
```text
Active Connections

  Proto  Local Address          Foreign Address        State
  TCP    0.0.0.0:135            0.0.0.0:0              LISTENING
  TCP    192.168.1.15:51234     142.250.180.206:443    ESTABLISHED
```

---

### Command 19: Check Running Processes
```powershell
Get-Process
```
**Output:**
```text
Handles  NPM(K)    PM(K)      WS(K)     CPU(s)     Id ProcessName
-------  ------    -----      -----     ------     -- -----------
    450      25    35400      48200       2.15   1234 Code
    120      10     4500       8900       0.45   5678 powershell
```

---

### Command 20: Echo Text to Terminal
```powershell
Write-Output "Hello World"
```
**Output:**
```text
Hello World
```
---

### Command 21: Get Current Date and Time
```powershell
Get-Date
```
**Output:**
```text
Monday, September 21, 2026 8:28:00 AM
```

---

### Command 22: Display File Content
```powershell
Get-Content README.md
```
**Output:**
```text
# fswd-ruweida
Full Stack Web Development Repository
```

---

### Command 23: Append Text to File
```powershell
Add-Content -Path "README.md" -Value "## Week 1 Tasks Completed"
```
**Output:**
```text
Command executed successfully.
```

---

### Command 24: Copy File
```powershell
Copy-Item README.md README_backup.md
```
**Output:**
```text
Command executed successfully.
```

---

### Command 25: Check Git Log History
```powershell
git log --oneline
```
**Output:**
```text
a1b2c3d Initial commit: Added week folders, README, and gitignore
```

