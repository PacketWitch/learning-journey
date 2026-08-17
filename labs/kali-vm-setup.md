# Kali Linux Virtual Lab

## Objective

Set up an isolated Kali Linux environment for hands-on
cybersecurity learning and experimentation.

## Host Environment

- Host OS: Windows 11
- CPU: Intel Core i7-13620H
- RAM: 16 GB
- GPU: NVIDIA RTX 4050
- Virtualization: VMware Workstation Pro

## Kali Linux VM

- OS: Kali Linux
- RAM: 4 GB
- CPUs: 4
- Virtual Disk: ~80 GB
- Network Adapter: NAT

## Setup

1. Downloaded the Kali Linux VMware image.
2. Extracted the VMware virtual machine.
3. Opened the `.vmx` configuration in VMware Workstation.
4. Configured the VM resources.
5. Started Kali Linux.
6. Logged into the Kali desktop.
7. Verified network connectivity.

## Network Verification

Tested connectivity using:

```bash
ping -c 4 google.com
