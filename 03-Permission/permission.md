# 🔐 File Permissions in Terminal

File permissions control who can read, write, or execute a file.

---

## 🧠 Basic Concept

There are 3 types of users:

- User (owner)
- Group
- Others

And 3 types of permissions:

- Read (r)
- Write (w)
- Execute (x)

---

## 📌 1. Check Permissions

```bash
ls -l
```

#### Example output:

```bash 
-rwxr-xr-- file.txt
```

### 👉 Breakdown:

* rwx → owner permissions
* r-x → group permissions
* r– → others permissions


## 📌 2. Change Permissions (chmod)

### 👉 Add permission

```bash 
chmod +x file.txt
```

### 👉 Remove permission

```bash 
chmod -w file.txt
```

### 👉 Set exact permission

```bash 
chmod 755 file.txt
```

### 👉 Meaning of 755:

* 7 = rwx
* 5 = r-x
* 5 = r-x


## 📌 3. Change Ownership (chown)

```bash 
chown user:group file.txt
```

## ⚠️ Common Mistakes

❌ Giving full permission (777) to everything
❌ Not understanding execute permission


## 🧠 Pro Tips

* Use 755 for scripts
* Use 644 for normal files
* Avoid 777 unless absolutely necessary

## 🚀 Summary

* ls -l → check permissions
* chmod → change permissions
* chown → change ownership