# NNmap Commands I Practiced
# 1) Basic Scan
nmap 192.168.1.0
# Purpose:
Discovers open ports on a target host.
# What I learned:
This command performs a basic scan and quickly reveals which ports are open. It showed me how reconnaissance begins with gathering visible network information.

# 2) Service Version Detection
nmap -sV 192.168.1.0
# Purpose:
Detects services running on open ports and attempts to identify their versions.
# What I learned:
Understanding service versions is important because outdated software versions may contain known vulnerabilities.

# 3) OS Detection
nmap -O 192.168.1.0
# Purpose:
Attempts to identify the operating system of the target host.
# What I learned:
Operating system fingerprinting helps security professionals understand their target environment before deeper testing.

# 4) Aggressive Scan
nmap -A 192.168.1.0
# Purpose:
Runs a more comprehensive scan including version detection, OS detection, scripts, and traceroute.
# What I learned:
Aggressive scans provide rich information but should be used thoughtfully because they are noisy and more detectable.

# 5) TCP Connect Scan
nmap -sT target
# Purpose:
A full TCP three-way handshake scan.
# What I learned
This is one of the most basic scan methods. It completes a full connection with the target, making it reliable but easier to detect.

# 6) SYN Scan
nmap -sS target
# Purpose:
A half-open scan, often called a stealth scan.
# What I learned:
This scan does not complete the full TCP handshake, making it faster and less obvious than a TCP Connect scan.

# 7) UDP Scan
nmap -sU target
# Purpose:
Scans UDP ports instead of TCP ports.
# What I learned:
Many important services use UDP, including DNS and DHCP. UDP scanning can reveal services that TCP scans miss.

# Reflection
One thing that surprised me is how much useful information can be gathered from simple reconnaissance. This reinforced for me that information gathering is one of the most 
critical stages in ethical hacking.




