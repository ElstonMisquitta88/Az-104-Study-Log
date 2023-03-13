# Az-104-Study-Log

**(1) Deploy and Manage Azure Compute resources**

> **01/03/2023**

- [x] Buliding a Windows Virtual Machine
- [x] Connecting to a VM
- [x] VM Machine Disks
- [x] Az Disk - Server Side Encryption
```
Azure Disk Storage Server-Side Encryption (also referred to as encryption-at-rest or Azure Storage encryption)
automatically encrypts data stored on Azure managed disks (OS and data disks) when persisting on the Storage Clusters.
When configured with a Disk Encryption Set (DES), it supports customer-managed keys as well
```
- [x] Disk Encryption Sets
```
Disk Encryption Set is a new resource introduced for simplifying the key management for managed disks. 
When a disk encryption set is created, a system-assigned managed identity is created in Azure Active Directory (AD)
and associated with the disk encryption set.
```
- [x] Azure Disk Encryption
```
Azure Disk Encryption helps protect and safeguard your data to meet your organizational security and compliance commitments. 
ADE encrypts the OS and data disks of Azure virtual machines (VMs) inside your VMs 
by using the DM-Crypt feature of Linux or the BitLocker feature of Windows. 
ADE is integrated with Azure Key Vault to help you control and manage the disk encryption keys and secrets
```



> **13/03/2023**

- [x] Data Disk Snapshots
```
A snapshot is a full, read-only copy of a virtual hard disk (VHD). 
You can use a snapshot as a point-in-time backup, or to help troubleshoot virtual machine (VM) issues.
You can take a snapshot of both operating system (OS) or data disk VHDs.
```

- [X] Azure Shared Disks
```
Azure shared disks is a feature for Azure managed disks that allow you to attach a managed disk
to multiple virtual machines (VMs) simultaneously. 
Attaching a managed disk to multiple VMs allows you to either deploy new or migrate existing clustered applications to Azure.
```
- [ ] Custom Script Extensions
