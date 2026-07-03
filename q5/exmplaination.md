# Q5 Explanation

- Ran lsblk to identify physical and loop block devices available to the environment.
- Used mount to confirm filesystems mounted on /, /proc, /dev, /dev/pts, and /sys.
- Used df -h to capture disk usage and free space for mounted filesystems.
- Used df -i to check inode availability and verify there is no inode exhaustion.
- Noted that /dev/root has the highest used percentage and should be monitored for future deployment storage.
