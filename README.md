project: Task 9 - Network Vulnerability Scanning

author: Mounika

objective: 
  To perform network vulnerability scanning using Nmap in order to
  identify live hosts, open ports, running services, operating system
  details, and possible security risks in a local network.

tools:
  - Nmap
  - Ubuntu Linux

target:
  network_range: 172.16.97.128/24
  target_host: 172.16.96.129

steps_performed:
  - Discovered active hosts using ping scan
  - Scanned target for open ports
  - Detected services and versions
  - Identified operating system
  - Performed vulnerability scanning
  - Analyzed security risks
  - Documented findings

files:
  report: Network_Scan_Report.pdf
  screenshots:
    - 1_nmap_version.png
    - 2_network_range.png
    - 3_live_hosts.png
    - 4_open_ports.png
    - 5_services.png
    - 6_os_detection.png
    - 7_vulnerabilities.png

outcome: 
  This task helped me understand how network reconnaissance and
  vulnerability scanning are performed in real-world security testing.
  I learned how attackers identify systems and how defenders can find
  security weaknesses before they are exploited.
