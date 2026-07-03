# Q2 Explanation

- Created the secure_workspace directory and its child directories docs, src, and logs.
- Created placeholder files plan.txt, app.txt, and activity.log for project documentation and logs.
- Applied directory permissions 750 to restrict access to owner and group and deny others.
- Applied file permissions 640 so only the owner can write and the group can read.
- Checked umask, which is 0022, and it ensures newly created files are not world-writable.
