# NNmap Commands I Practiced
# 1) Basic Scan
nmap 192.168.1.0
# Purpose:
Discovers open ports on a target host.
# What I learned:
This command performs a basic scan and quickly reveals which ports are open. It showed me how reconnaissance begins with gathering visible network information.

# 2) Service Version Detection
nmap -sV scanme.nmap.org
# Purpose:
Detects services running on open ports and attempts to identify their versions.
# What I learned:
Understanding service versions is important because outdated software versions may contain known vulnerabilities.

# 3) OS Detection
nmap -O scanme.nmap.org
# Purpose:
Attempts to identify the operating system of the target host.
# What I learned:
Operating system fingerprinting helps security professionals understand their target environment before deeper testing.

# 4) Aggressive Scan
nmap -A scanme.nmap.org
# Purpose:
Runs a more comprehensive scan including version detection, OS detection, scripts, and traceroute.
# What I learned:
Aggressive scans provide rich information but should be used thoughtfully because they are noisy and more detectable.
