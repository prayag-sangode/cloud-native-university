# Lab 03: Process Management

## Objective
Learn how to monitor and control running processes in Linux.

## Step 1: View system processes

```bash id="s1"
ps aux
```

## Step 2: Real-time monitoring
```
top
```
Press q to exit

## Step 3: Check system memory
```
free -m
```

## Step 4: Check disk usage
```
df -h
```

## Step 5: Run a background process
```
sleep 100 &
```

## Step 6: Find process ID
```
ps aux | grep sleep
```

## Step 7: Kill process
```
kill <PID>
```

If it doesn't stop:
```
kill -9 <PID>
```

## Expected Output

### You should be able to:

- View system processes
- Monitor CPU and memory
- Run background processes
- Kill processes safely

## Real-world connection

### This is used when:

- Kubernetes pods crash or hang
- EC2 instances go high CPU
- Docker containers freeze
- CI/CD pipelines get stuck
