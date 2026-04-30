## 🔎 grep Command

The `grep` command is used to search for text inside files.

### 📌 Basic Syntax

```bash
grep "text" file.txt
```

### 📌 Examples

#### 👉 Search word in file

```bash 
grep "hello" file.txt
```

#### 👉 Ignore case

```bash 
grep -i "hello" file.txt
```

#### 👉 Search in all files

```bash 
grep -r "hello" .
```

#### 👉 Show line numbers

```bash
grep -n "hello" file.txt
```

## ⚠️ Common Mistakes

❌ Case sensitivity issues
❌ Forgetting quotes


## 🧠 Pro Tips

* Combine find + grep for powerful searching
* Use -r for recursive search

## 🚀 Summary

* grep → search text
* find → search files