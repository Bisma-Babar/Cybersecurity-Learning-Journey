# Nmap Basic Scanning Lab

## Objective
Learn how to identify open ports and services using Nmap.

## Tool Used
- Nmap 7.99

## Target
localhost (127.0.0.1)

## Commands Used

Basic scan:
nmap localhost

Service detection:
nmap -sV localhost

## Results
| Port | State | Service |
|---|---|---|
| 135/tcp | Open | Microsoft Windows RPC |
| 445/tcp | Open | Microsoft-DS (SMB) |

## Learning Outcome
Learned:
- How port scanning works
- How to identify open ports
- How services can create security risks

## Security Importance
Open ports increase the attack surface. Security professionals use port scanning to identify unnecessary exposed services and improve security.
