# Managing-Incident-Response-Mitigation-and-Recovery

## Objective

In this lab, I performed a forensic analysis, implemented security controls in Windows and Linux environments, and demonstrated backup and recovery processes. The goal was to showcase key cybersecurity skills such as forensic disk imaging, validating data integrity, centralizing logs, applying group policies, and enforcing security rules using AppLocker.

### Skills Learned

- Forensic Data Handling and Integrity Validation:
    - Creation of forensic disk images using dd.
    - Generating and validating file hashes for data integrity with md5sum
    - Simulating data changes and re-verifying integrity.
- Access Control and Security Policy Implementation:
    - Configuring and applying Group Policy Objects (GPOs) in Active Directory.
    - Implementing AppLocker rules to restrict user access to files and executables.
    - Enforcing path-based restrictions for controlled user groups.
- Log Centralization and Management:
    - Configuring a Linux server as a centralized syslog server.
    - Forwarding logs from remote clients to the centralized server.
    - Managing firewall rules for secure log transmission.
- Backup and Recovery Management:
    - Backing up critical data to a remote location.
    - Simulating data loss and recovering data from a backup.
    - Validating successful file recovery and ensuring business continuity.
- Networking and System Configuration:
    - Managing firewall rules for UDP log transmission.
    - Editing system configuration files for syslog and AppLocker.

 ## Tools Used

- **Kali Linux:** Used as a remote client to forward logs to the centralized server.
- **AppLocker:** Used for creating and enforcing access control policies to restrict file and application usage.
- **Firewall (UFW on Linux):** Configured to allow specific traffic (UDP for syslog).
- **Group Policy Management Console (GPMC):** Applied AppLocker rules for access control.
- **Windows Server Backup:** Performed backup and recovery tasks.
- **Windows Firewall:** Managed security rules for server protection.

## Steps
**1.Created a forensic disk image:**
 I used the dd command to create an image of a victim file from the disk:
