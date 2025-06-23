
# Task 1 - Port Scanning using Nmap

## Objective:
Perform a TCP SYN scan on the local network using `nmap -sS`.

## My IP Range Scanned:
192.168.10.0/24

## Devices & Open Ports Found:
| IP Address     | Open Ports  |
|----------------|-------------|
| 192.168.10.1   | 21,22,80,443|
| 192.168.10.11  | 49152,62078 |
| 192.168.10.9   | 22          |

## Risks Identified:
- Open port 21, 22, 80, 443	FTP and HTTP are weak if unencrypted; SSH should be hardened.
- Open port 49152, 62078	Could expose private services; needs further inspection.
- Open port 22	SSH must be hardened to avoid brute-force login.

## Tools Used:
- Nmap
- (Optional) Wireshark

## Key Learnings:
- Identified open services on LAN
- Understood which ports/services are potential risks

