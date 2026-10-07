# System Baseline Report

## Host Resource Baseline

Before deploying any application, it is important to establish a clear baseline of the host server’s resources. This report documents the memory and disk capacity of the KillerCoda Ubuntu Playground used in this laboratory activity.

### Memory (RAM)

- **Total RAM available on the server:** 1.9 GiB

### Disk Storage

- **Total Storage capacity of the root (/) file system:** 19G

### Why Checking Disk Space is Critical

Checking available disk space before a massive traffic surge is critical because logs, temporary files, and container images can quickly fill up the storage. If the disk becomes full, the server may fail to write new data, causing applications to crash or become unresponsive during high load.

---

**Screenshots:**
- `screenshots/memory-check.png`
- `screenshots/disk-check.png`
