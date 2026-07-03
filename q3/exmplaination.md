# Q3 Explanation

- Created original.txt, then made a hard link hardlink.txt and a symbolic link symlink.txt.
- Verified that original.txt and hardlink.txt share the same inode number, while symlink.txt has a different inode.
- Confirmed all three paths initially return the same file contents.
- After deleting original.txt, the hard link still accesses the data because it references the same inode.
- The symbolic link breaks when the original file is removed because it points to the original path.
