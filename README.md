# Guix System Installation on VirtualBox

## Project
Installation of GNU Guix System 1.5.0 on Oracle VM VirtualBox for an Operating System and System Programming assignment.

## Author
Mulugeta Alemneh

## VM Configuration
- VM Name: Guix_system_Mulugetaalemneh
- OS Type: Other Linux (64-bit)
- RAM: 8 GB (increased from 4.5 GB)
- CPU: 4 cores (increased from 2)
- Disk: 30 GB dynamically allocated
- Filesystem: ext4 (root) + linux-swap

## Issues Solved
- Enabled VT-x in BIOS (was disabled causing VM to abort)
- Bypassed VirtualBox unattended installation
- Fixed Python 3.5.9 build error by increasing RAM and CPU

## Tools Used
- Oracle VM VirtualBox 7.0+
- GNU Guix System 1.5.0 ISO
- Windows 11 Host

## Conclusion
Guix System installed successfully with user account Mulugeta Alemneh.

## Full Documentation
See `DOCUMENTATION.md` for complete report with screenshots and all sections (a to j).
