# Linux Users & Permissions

## Objective

Understand how Linux controls users, access, and file permissions — a core concept for AWS, Kubernetes, and production security.

# Why This Matters

In real systems:

- AWS uses IAM (similar concept)
- Kubernetes uses RBAC (role-based access)
- Docker containers run with limited users
- Linux controls everything via permissions

If permissions are wrong → systems fail or become insecure.

# Linux Users

Linux is a **multi-user system**.

Types of users:

## 1. Root user
- Full access
- Can do anything
- Dangerous if misused

## 2. Regular user
- Limited access
- Safer for daily work

## 3. Service users
- Used by applications (e.g., nginx, docker)

# File Permissions

Each file has 3 types of permissions:

```text id="perm1"
r = read
w = write
x = execute
```

## Permission Structure

Example:

-rwxr-xr--

## Breakdown:

Section	Meaning
rwx	Owner permissions
r-x	Group permissions
r--	Others permissions

## Important Commands
### Check user
```
whoami
```
### Switch user
```
su - username
```

### Check file permissions
```
ls -l
```

### Change permissions
```
chmod 755 file.sh
```

### Change ownership
```
chown user:user file.txt
```

# Real-world usage
- AWS EC2 access control
- Kubernetes pod security
- Docker container user restrictions
- CI/CD pipeline permissions

# Outcome

## After this module you will understand:

- Linux user system
- File permission model
- How access control works
- Foundation for cloud security
