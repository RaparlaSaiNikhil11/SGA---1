# Q4 Explanation

- Deleted old log files and created app.log for the investigation.
- Used lsof to inspect open files across the system and then focused on the current shell process.
- Opened app.log on file descriptor 3 and confirmed it appears under /proc/$$/fd.
- Redirected stdout and stderr to separate files and then combined both streams into combined.txt.
- Checked ulimit to review file descriptor and process limits, which shows the shell allows many open files.
