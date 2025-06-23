
# Task 1 - Port Scanning using Nmap

## Objective:
Perform a TCP SYN scan on the local network using `nmap -sS`.

## My IP Range Scanned:
192.168.1.0/24

## Devices & Open Ports Found:
| IP Address     | Open Ports  |
|----------------|-------------|
| 192.168.1.1    | 80, 443     |
| 192.168.1.5    | 22, 80      |
| 192.168.1.10   | 139, 445    |
| 192.168.1.15   | 21, 23      |

## Risks Identified:
- Open port 21 (FTP) and 23 (Telnet) can be security risks if unencrypted.
- Port 139 and 445 indicate SMB — often targeted in lateral movement attacks.

## Tools Used:
- Nmap
- (Optional) Wireshark

## Screenshot:
*(Add screenshot if you took any)*

## Key Learnings:
- Identified open services on LAN
- Understood which ports/services are potential risks

