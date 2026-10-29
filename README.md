**NETWORKWALKS-B084-WK1-PM1-CYBERSECURITY-LAB-SETUP**

## Networkwalks Week 1 — Cybersecurity Lab Setup

### 1. Project Overview

This project documents the setup of a cybersecurity testing lab using Oracle VirtualBox and Kali Linux as part of the Networkwalks Cybersecurity Internship.

### 2. Lab Environment

- **Host operating system:** Windows (version to be confirmed)
- **Virtualization platform:** Oracle VirtualBox
- **Guest operating system:** Kali Linux (version to be confirmed)
- **NAT Network subnet:** `10.0.0.0/24`
- **Kali Linux IPv4 address:** `10.0.0.2/24`
- **Gateway tested:** `10.0.0.1`
- **Shared host folder:** `C:\downloads`
- **Shared folder name:** `downloads`

### 3. Project Objectives

- Configure a VirtualBox NAT Network using the required subnet.
- Configure Kali Linux with the required IPv4 address.
- Test local gateway connectivity.
- Test internet connectivity.
- Configure a shared folder between the Windows host and Kali Linux guest.
- Enable bidirectional clipboard and drag-and-drop.
- Create a VirtualBox snapshot.

### 4. Network Configuration

The Kali Linux virtual machine was configured with the required IPv4 address:

`10.0.0.2/24`

The NAT Network subnet is:

`10.0.0.0/24`

### 5. Connectivity Testing

The following connectivity tests were performed:

**Gateway test**
```bash
ping -c 4 10.0.0.1
```

**Result:** Successful; 0% packet loss.

**Internet connectivity test**
```bash
ping -c 4 www.networkwalks.com
```

**Result:** Successful; 0% packet loss.

### 6. Shared Folder and VirtualBox Integration

The Windows host folder `C:\downloads` was configured as a VirtualBox shared folder named `downloads`.

Bidirectional shared clipboard and drag-and-drop were enabled in the VirtualBox settings.

### 7. Evidence Screenshots

Screenshots will be added to this repository after they have been captured.

Planned evidence:

1. Kali Linux IP configuration.
2. Successful gateway connectivity test.
3. Successful internet connectivity test.
4. VirtualBox shared-folder configuration.
5. Shared folder accessible from Kali Linux.
6. VirtualBox snapshot.

### 8. Conclusion

The Kali Linux virtual machine was configured with the required IPv4 address. Gateway and internet connectivity were tested successfully. The shared-folder and VirtualBox integration settings were configured.

### 9. Internship Details

- **Intern:** Walter Muzanenhamo
- **Program:** Networkwalks Cybersecurity Internship
- **Project:** WK1-PM1
