# 📍 Absolute vs Relative Path

Paths define the location of files and folders in the system.


## 🧠 1. Absolute Path

### 👉 Full path from root directory

#### Example:
```bash
/Users/pratyush/Documents/file.txt
```

✔ Always starts with /
✔ Works from anywhere



## 🧠 2. Relative Path

### 👉 Path relative to current directory

#### Example:

```bash 
../file.txt
```

✔ Does NOT start with /
✔ Depends on current location

## 🧠 Example

### Current folder:

```bash 
/home/user/docs
```

### 👉 Absolute:

```bash 
/home/user/docs/file.txt
```

### 👉 Relative:

```bash
file.txt
```

## ⚠️ Common Mistakes

❌ Confusing . and ..
❌ Using wrong path → command fails



## 🚀 Summary

* Absolute → full path
* Relative → depends on current location
* . = current
* .. = parent