# Lab 01: Basic Linux Commands

## Objective
Practice essential Linux navigation and file operations.

---

# Step 1: Check system info

```bash id="s1"
uname -a
```

# Step 2: Check current directory
```
pwd
```
# Step 3: List files
```
ls
ls -l
```

# Step 4: Create directory
```
mkdir cloud-native-lab
cd cloud-native-lab
```

# Step 5: Create files
```
touch file1.txt file2.txt
ls
```

# Step 6: Add content to file
```
echo "Welcome to Cloud Native University" > file1.txt
cat file1.txt
```

# Step 7: Delete file
```
rm file2.txt
ls
```

# Expected Output

You should be able to:

- Navigate Linux system
- Create files and folders
- Read file content
- Delete files safely

# Real-world connection

These same commands are used when:

- Debugging AWS EC2 instances
- Inspecting Kubernetes nodes
- Working inside Docker containers
- Checking logs in production systems
  
