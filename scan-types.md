# Nmap Scan Types
# 1) TCP Connect Scan
nmap -sT target
# What it is: 
A full TCP three-way handshake scan.
# What I learned:
This is one of the most basic scan methods. It completes a full connection with the target, making it reliable but easier to detect.
# Best use:
Basic scanning and learning how connections are established.

# 2) SYN Scan
nmap -sS target
# What it is:
A half-open scan, often called a stealth scan.
# What I learned:
This scan does not complete the full TCP handshake, making it faster and less obvious than a TCP Connect scan.
# Best use:
Reconnaissance and stealthier port scanning

# 3) UDP Scan
nmap -sU target
# What it is:
Scans UDP ports instead of TCP ports.
# What I learned:
Many important services use UDP, including DNS and DHCP. UDP scanning can reveal services that TCP scans miss.
# Best use:
Discovering UDP-based services.

# 4) Service Version Detection
nmap -sV target
# What it is:
Attempts to identify service versions running on open ports.
# What I learned:
Knowing the exact software version helps identify potential vulnerabilities and outdated services.
# Best use
Vulnerability assessment and service enumeration.
# Reflection
Learning different scan types helped me understand that reconnaissance is not just about finding open ports. It is about choosing the right technique for the information you need.



