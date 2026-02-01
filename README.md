# Build-002
# Hardware Specifications: Build-002 (Hypervisor Host / Security Sandbox)

## System Configuration
| Component | Model/Specification | Notes |
| :--- | :--- | :--- |
| **CPU** | Intel Core i7-7700 @ 3.6GHz | |
| **Cooling** | Hyper 212 CPU Cooler | |
| **Motherboard** | ASUS H110 Plus | |
| **GPU** | MSI GTX 1080 Gaming X 8G | Recently serviced by ChrisTrahan-sec with Thermal Grizzly compound |
| **PSU** | Corsair 650W Silver Rated | |

## Storage Configuration (Virtualized Lab Environment)
| Drive | Size | Status | Purpose |
| :--- | :--- | :--- | :--- |
| **C: Drive (SSD)** | 110GB SATA | 14.9GB Free | Windows 11 Host OS |
| **D: Drive (HDD)** | 596GB SATA | 596GB Free | Dedicated Virtual Machine Storage (The "Cyber Range") |
| **F: Drive (HDD)** | 931GB SATA | 878GB Free | Temp/Cache/Residual File Storage |

## Security Lab Role
This machine is configured as the dedicated host for VirtualBox VMs, running Ubuntu, Kali Linux, and Metasploitable targets in an isolated network environment.
*Note: This system was entirely assembled, wired, and configured by hand from individual components.*