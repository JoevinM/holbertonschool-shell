# 🔐 Permissions - Shell Scripts for File Ownership & Permissions

Scripts to manipulate file ownerships, permissions, and groups in Linux.

---

## 🔧 Scripts Overview

| #  | Title                | Goal                                                                                          |
| -- | -------------------- | --------------------------------------------------------------------------------------------- |
| 0  | My name is Betty     | Switch the current user to the user `betty`.                                                  |
| 1  | Who am I             | Print the effective username of the current user.                                             |
| 2  | Groups               | Print all the groups the current user belongs to.                                             |
| 3  | New owner            | Change the owner of the file `hello` to user `betty`.                                         |
| 4  | Empty!               | Create an empty file called `hello`.                                                          |
| 5  | Execute              | Add execute permission to the owner of the file `hello`.                                      |
| 6  | Multiple permissions | Add execute permission to owner and group owner, and read permission to others on `hello`.    |
| 7  | Everybody!           | Add execute permission to owner, group owner, and others on the file `hello`.                 |
| 8  | James Bond           | Set file `hello` permissions: owner and group no permissions, others full permissions.        |
| 9  | John Doe             | Set mode of file `hello` to `-rwxr-x-wx` (specific permissions and ownership info).           |
| 10 | Look in the mirror   | Set mode of file `hello` the same as file `olleh`.                                            |
| 11 | Directories          | Add execute permission to owner, group, and others to all subdirectories (not regular files). |
| 12 | More directories     | Create directory `my_dir` with permissions `751` in current directory.                        |
| 13 | Change group         | Change group owner of file `hello` to `school`.                                               |
| 14 | Owner and group      | Change owner to `vincent` and group to `staff` for all files and directories in current dir.  |
| 15 | Symbolic links       | Change owner and group of `_hello` to `vincent` and `staff`.                                  |
| 16 | If only              | Change owner of file `hello` to `vincent` only if currently owned by user `guillaume`.        |


---
