# Linux Best Practices

## 1. Always check logs
```bash
/var/log/
journalctl -xe
```
## 2. Avoid running as root
Use sudo only when required

## 3. Monitor system usage
```
top
htop
```

## 4. Keep system clean
```
apt clean
yum clean all
```

## 5. Secure SSH access
Disable password login
Use key-based authentication



```text
Linux → Docker → Kubernetes → AWS → EKS
