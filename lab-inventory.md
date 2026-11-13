# Hyper-V Lab Inventory

This page lists the virtual machines, networks and checkpoints in my Hyper-V lab, so each course can point to the right machine.

## How to fill this in
Open **PowerShell as administrator** on the computer that runs Hyper-V and run these commands. Copy the results into the tables below.

```powershell
Get-VM | Select-Object Name, State, Generation, ProcessorCount, MemoryAssigned | Format-Table
Get-VMSwitch | Select-Object Name, SwitchType | Format-Table
Get-VMNetworkAdapter -VMName * | Select-Object VMName, SwitchName | Format-Table
Get-VMCheckpoint -VMName * | Select-Object VMName, Name, CreationTime | Format-Table
```

Do not paste passwords, product keys or public IP addresses.

## Virtual machines
| VM name | Role | Course | State |
|---|---|---|---|
| (domain controller) | Active Directory, DNS | Windows Server | |
| (file server) | File server, IIS, FTP | Windows Server | |
| | | | |

## Virtual switches
| Switch name | Type | Used by |
|---|---|---|
| | | |

## Checkpoints
| VM | Checkpoint | Created | Purpose |
|---|---|---|---|
| | | | |
