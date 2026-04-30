# 🔍 find Command

The `find` command is used to search for files and directories in a directory hierarchy.

### 📌 Basic Syntax

```bash
find <path> <condition>
```

### 📌 Examples

#### 👉 Find file by name

```bash
find . -name "file.txt"
```

#### 👉 Find all Python files

```bash 
find . -name "*.py"
```

#### 👉 Find directories only

```bash 
find . -type d
```

#### 👉 Find files only

```bash 
find . -type f
```

### ⚠️ Common Mistakes

❌ Forgetting quotes in "*.py"
❌ Searching in wrong directory

### 🧠 Pro Tips

* Use . to search in current directory
* Combine with other commands for power usage

### 🚀 Summary

* find → search files/folders
* Works recursively