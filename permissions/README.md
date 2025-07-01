# 🔐 Permissions - Shell Scripts for File Ownership & Permissions

Scripts to manipulate file ownerships, permissions, and groups in Linux.

---

## 🔧 Scripts Overview

### 🔹 0. My name is Betty
- **Goal:** Switch the current user to the user `betty`.

---

### 🔹 1. Who am I
- **Goal:** Print the effective username of the current user.

---

### 🔹 2. Groups
- **Goal:** Print all the groups the current user belongs to.

---

### 🔹 3. New owner
- **Goal:** Change the owner of the file `hello` to the user `betty`.

---

### 🔹 4. Empty!
- **Goal:** Create an empty file called `hello`.

---

### 🔹 5. Execute
- **Goal:** Add execute permission to the owner of the file `hello`.

---

### 🔹 6. Multiple permissions
- **Goal:** Add execute permission to owner and group owner, and read permission to others on file `hello`.

---

### 🔹 7. Everybody!
- **Goal:** Add execute permission to owner, group owner, and others on the file `hello`.

---

### 🔹 8. James Bond
- **Goal:** Set permissions on `hello` to:
  - Owner: no permission
  - Group: no permission
  - Others: all permissions

---

### 🔹 9. John Doe
- **Goal:** Set the mode of file `hello` to `-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello`.

---

### 🔹 10. Look in the mirror
- **Goal:** Set the mode of file `hello` the same as file `olleh`.

---

### 🔹 11. Directories
- **Goal:** Add execute permission for owner, group, and others to *all subdirectories* in the current directory. Do not change regular files.

---

### 🔹 12. More directories
- **Goal:** Create a directory called `my_dir` with permissions `751` in the current working directory.

---

### 🔹 13. Change group
- **Goal:** Change the group owner of file `hello` to `school`.

---

### 🔹 14. Owner and group
- **Goal:** Change owner to `vincent` and group to `staff` for *all* files and directories in the working directory.

---

### 🔹 15. Symbolic links
- **Goal:** Change owner and group owner of `_hello` to `vincent` and `staff`, respectively.

---

### 🔹 16. If only
- **Goal:** Change owner of file `hello` to `vincent` *only if* it is currently owned by user `guillaume`.

---
