# red-hat-ex200-rhcsa-study-guide
Community study guide for Red Hat EX200 RHCSA, covering RHEL 10 administration, storage, networking, SELinux, security, services, scripting, and hands-on preparation.
# Red Hat EX200: RHCSA Study Guide

## Introduction

This repository is a practical study guide for the **Red Hat Certified System Administrator (RHCSA) Exam EX200**. It focuses on the skills required to administer Red Hat Enterprise Linux and is designed for Linux administrators, students, DevOps professionals, and candidates preparing through hands-on practice.

The current EX200 is based on **Red Hat Enterprise Linux 10** and is performance-based rather than a traditional multiple-choice exam.

## Exam Overview

| Item | Details |
|---|---|
| Vendor | Red Hat |
| Certification | Red Hat Certified System Administrator (RHCSA) |
| Exam | EX200 |
| Platform | Red Hat Enterprise Linux 10 |
| Purpose | Validate core RHEL system administration skills |
| Format | Performance-based, hands-on |
| Duration | 3 hours |
| Passing score | Verify the current requirement with Red Hat |
| Questions | No fixed multiple-choice question count; candidates complete practical tasks |
| Prerequisites | No mandatory prerequisite; RH124 + RH134, RH199, or comparable RHEL administration experience is recommended |

Red Hat states that EX200 tests real-world system administration skills and requires configurations to remain functional after reboot.

## Who Should Take It?

EX200 is suitable for:

- Linux/RHEL system administrators
- IT professionals working with enterprise Linux
- Students preparing for Linux administration careers
- DevOps professionals building RHEL skills
- Administrators progressing toward RHCE
- Experienced Linux professionals seeking RHCSA certification

Strong command-line experience is highly recommended.

## Exam Objectives / Domains

### 1. Essential Tools
Practice shell commands, redirection, pipes, grep, regular expressions, SSH, file operations, links, permissions, archives, and system documentation.

### 2. Software Management
Understand RPM repositories, package installation/removal, updates, and Flatpak package management.

### 3. Shell Scripting
Write simple Bash scripts using variables, arguments, `if`, tests, loops, and command output.

### 4. Running Systems
Manage boot targets, processes, scheduling priority, services, system logs, journals, and secure file transfers.

### 5. Local Storage
Work with GPT partitions, physical volumes, volume groups, logical volumes, UUIDs, labels, and swap.

### 6. File Systems
Create and manage XFS, ext4, and VFAT file systems; configure NFS, autofs, mounts, and logical-volume expansion.

### 7. System Deployment & Maintenance
Manage cron, `at`, systemd timers, services, boot targets, time synchronization, software repositories, packages, and bootloader configuration.

### 8. Networking
Configure IPv4/IPv6, hostnames, name resolution, network services, and firewall rules with NetworkManager and firewalld.

### 9. Users & Groups
Create and modify users/groups, manage passwords and aging, configure memberships, and administer privileged access.

### 10. Security
Practice firewalld, SSH key authentication, default permissions, SELinux modes, contexts, port labels, file-context restoration, and SELinux booleans.

## Detailed Study Notes

### File Permissions
Understand:
- `u`, `g`, `o`
- `r`, `w`, `x`
- `chmod`, `chown`, `chgrp`
- symbolic and numeric permissions
- default permissions and `umask`

Example:
```bash
chmod 640 report.txt
chown user:admins report.txt
