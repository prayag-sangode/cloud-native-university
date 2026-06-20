# Linux Architecture

## System Overview


Application
↓
Shell (bash/zsh)
↓
System Calls
↓
Linux Kernel
↓
Hardware (CPU, Memory, Disk)


---

## Key Components

### 1. Kernel
- Core of Linux
- Manages memory, CPU, devices

### 2. Shell
- Interface for users
- Executes commands

### 3. File System
- Everything is a file in Linux

---

## Example Flow

When you run:

```bash
ls
``` 

It goes:

Shell → Kernel → File system → Output
