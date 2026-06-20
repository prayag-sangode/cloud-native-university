# Linux Basic Commands

## Objective

Learn essential Linux commands used in cloud, DevOps, and production environments.

# What is Linux?

Linux is a multi-user, multi-tasking operating system used in:

- AWS EC2 servers
- Kubernetes worker nodes
- Docker containers
- CI/CD pipelines

# Why Basic Commands Matter

In real-world systems, you will:

- SSH into servers
- Inspect files and logs
- Debug applications
- Manage system resources

Without these commands, cloud environments are unusable.

# Linux Navigation Commands

## Print current directory
```bash
id="cmd1"
pwd
```

## List files
```
ls
ls -l
ls -a
```

## Change directory
```
cd /path
cd ..
cd ~
```

## File Operations

Create file
```
touch file.txt
```

## Create directory
```
mkdir my-folder
```

## Remove file/folder
```
rm file.txt
rm -r my-folder
```

## File Viewing Commands

## Show file content
```
cat file.txt
```

## Scroll large files
```
less file.txt
```

## Real-world usage

### These commands are used when:

Debugging EC2 instances
Checking logs in Kubernetes pods
Inspecting Docker containers
Troubleshooting CI/CD pipelines

## Outcome

### After this module, you will be able to:

✔ Navigate Linux filesystem
✔ Create and manage files
✔ Understand directory structure
✔ Use basic commands confidently in cloud systems
