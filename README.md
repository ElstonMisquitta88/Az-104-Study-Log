# Az-104-Study-Log

**(1) Deploy and Manage Azure Compute resources**

>**$\textcolor{red}{\textsf{01/03/2023}}$**

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



>**$\textcolor{red}{\textsf{13/03/2023}}$**

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

>**$\textcolor{red}{\textsf{14/03/2023}}$**
- [X] Custom Script Extensions
```
The Custom Script Extension downloads and runs scripts on Azure virtual machines (VMs). 
This extension is useful for post-deployment configuration, software installation, or any other configuration or management task. 
You can download scripts from Azure Storage or GitHub, or provide them to the Azure portal at extension runtime.
```

>**$\textcolor{red}{\textsf{27/03/2023}}$**
- [X] Boot Diagnostics
```
Troubleshoot the startup of an Azure Virtual Machine.
Use this feature to troubleshoot boot failures for custom or platform images.
Data will be stored in a storage account
```

- [X] AZ VM Run Command
```
The Run Command feature uses the virtual machine (VM) agent to run PowerShell scripts within an Azure Windows VM. 
You can use these scripts for general machine or application management. 
They can help you to quickly diagnose and remediate VM access and network issues and get the VM back to a good state.
```


- [X] Azure Confidential Computing
```
This is a feature that allows you to isolate sensitive data when it is being processed in the cloud.
This feature is available for your virtual machines. 
In Confidential computing , a part of the CPU’s hardware is reserved for the portion of code and data in your application.
This portion is known as an enclave.
```

- [X] Azure Dedicated Hosts
```
This service provides physical servers to host virtual machines. 
The physical server is dedicate to the Azure subscription.
The benefits of Azure Dedicated Hosts is that no other virtual machines from any other customers 
would be placed on the physical server.
You can also control the maintenance events that are initiated on the Azure platform.
```
