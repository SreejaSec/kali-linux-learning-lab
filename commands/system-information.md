# Kali Linux: System Information Commands

## Objective
Learn how to identify the current user, inspect Linux kernel information, and check the installed operating system version.

## Environment
- Operating System: Kali GNU/Linux Rolling 2026.2
- Architecture: x86_64

## 1. Identify the Current User

**Command:**
```bash
whoami
```

**Observed output:**
```text
kali
```

**Purpose:** Displays the username associated with the current terminal session.

## 2. Inspect Kernel Information

**Command:**
```bash
uname -a
```

**Purpose:** Displays information about the Linux kernel, system architecture, and build.

**Observation:** The output identified the kernel as `6.19.14+kali-amd64` and the architecture as `x86_64`.

## 3. Identify the Operating System

**Command:**
```bash
cat /etc/os-release
```

**Purpose:** Displays operating system identification information.

**Observation:** The system reported Kali GNU/Linux Rolling, version `2026.2`.

## Key Learnings
- `whoami` identifies the current user.
- `uname -a` displays kernel and system details.
- `/etc/os-release` contains operating system identification information.

## Conclusion
These commands provide a basic introduction to Linux system identification and are useful first steps when documenting a cybersecurity lab environment.

## Safety Note
These commands are informational and do not modify the system.
