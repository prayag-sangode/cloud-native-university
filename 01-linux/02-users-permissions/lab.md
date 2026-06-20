# Lab 02: Users & Permissions

## Objective
Learn how Linux manages users and file permissions.

## Step 1: Check current user

```bash id="s1"
whoami
```

## Step 2: Check user details
```
id
```

## Step 3: Create file
```
touch secure.txt
ls -l secure.txt
```

## Step 4: Change permissions

Make file read-only:
```
chmod 444 secure.txt
ls -l secure.txt
```

## Step 5: Try writing to file
```
echo "test" > secure.txt
```

You should get permission denied

## Step 6: Restore permissions
```
chmod 644 secure.txt
echo "test" > secure.txt
cat secure.txt
```

## Step 7: Change ownership (optional sudo)
```
sudo chown root:root secure.txt
ls -l secure.txt
```

# Expected Output

# You should understand:

- How permissions control access
- How chmod affects files
- Why root access is powerful
- How ownership works

# Real-world connection

## This is used in:

- AWS EC2 security control
- Kubernetes pod security contexts
- Docker container user restrictions
- CI/CD pipeline security rules
