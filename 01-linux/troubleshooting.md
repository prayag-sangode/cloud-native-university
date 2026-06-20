# Linux Troubleshooting

## Issue 1: Command not found

### Cause:
Package not installed or PATH issue

### Fix:
```bash
which <command>
echo $PATH
```

## Issue 2: Permission denied
### Fix:
```
chmod +x file.sh
sudo <command>
```

## Issue 3: High CPU usage
### Fix:
```
top
ps aux --sort=-%cpu
kill -9 <pid>
```

## Issue 4: Disk full
### Fix:
```
df -h
du -sh *
```
