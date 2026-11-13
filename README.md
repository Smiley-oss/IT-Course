# Windows Server (Haaga-Helia, ICI001ASA)

A hands-on course where I build and manage a Windows Server environment in a Hyper-V lab. The coursework is one cumulative report that grows after each task.

## Lab setup
- Hyper-V virtual lab on my own computer
- A domain controller VM (Active Directory and DNS)
- A file server VM (also used as the web and FTP server)
- One internal lab domain

## Tasks
| Task | Topic | Status |
|---|---|---|
| DNS | Name resolution: forward lookup zone, reverse lookup zone, host (A) and alias (CNAME) records, forwarder | Done |
| 9 | Web sites: HTTP and FTP server with IIS on the file server | In progress |
| Others | To be added as I finish them | Planned |

## What I learned so far
- How DNS turns names into IP addresses and back (forward and reverse zones)
- How to create and test A and CNAME records
- Why a DNS forwarder is used for names outside the lab
- How IIS hosts web sites and how FTP is added on a Windows file server (in progress)

## Notes on the report
Each task section has a short explanation, the required screenshots and a learning diary. The full report is handed in as a PDF, so this repository only holds a summary.
