# Linux Process Management

## Objective

Understand how Linux handles processes and how to monitor and control them — essential for debugging servers, containers, and cloud workloads.

# What is a Process?

A process is a running instance of a program.

Example:
- When you run `nginx` → it becomes a process
- When you run `python app.py` → it becomes a process

# Why it matters in Cloud

In real systems:

- Kubernetes runs hundreds of processes per node
- Docker containers are processes
- AWS EC2 hosts multiple running services

If processes fail → applications go down.

# Types of Processes

## 1. Foreground process
- Runs in terminal
- Blocks shell

## 2. Background process
- Runs without blocking terminal

## 3. Daemon process
- System services (e.g., sshd, nginx)

# Process Monitoring Commands

## View running processes
```bash id="cmd1"
ps aux
```
## Real-time monitoring
```
top
```

## Better UI tool (if installed)
```
htop
```

## Process Control Commands
Kill a process
```
kill <PID>
```

## Force kill
```
kill -9 <PID>
```

## Resource Monitoring
CPU, memory, disk usage
```
df -h
free -m
```

## Real-world usage
- Debugging high CPU in EC2
- Fixing crashed Kubernetes pods
- Killing stuck Docker containers
- Monitoring production workloads

## Outcome

### After this module you will:

- Understand Linux processes
- Monitor system performance
- Kill problematic processes
- Debug production issues
