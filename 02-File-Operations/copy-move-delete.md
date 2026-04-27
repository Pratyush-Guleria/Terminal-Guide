# 📁 Copy, Move & Delete in Terminal

These commands are used to manage files and folders.


## 📌 1. Copy Files (cp)

### 👉 Copy file

```bash
cp file.txt copy.txt
```

### 👉 Copy folder

```bash 
cp -r folder1 folder2
```
### 👉 -r means recursive (copy entire folder)

## 📌 2. Move Files (mv)

### 👉 Move file

```bash 
mv file.txt /path/to/destination/
```

### 👉 Rename file

```bash 
mv old.txt new.txt
```
### 👉 mv is also used for renaming

## 📌 3. Delete Files (rm)

### 👉 Delete file

```bash 
rm file.txt
```

### 👉 Delete folder
```bash 
rm -r folder/
```

### 👉 Force delete (⚠️ dangerous)
```bash 
rm -rf folder/
```

## ⚠️ Danger Zone

❌ rm -rf deletes everything permanently
❌ No recycle bin (cannot recover easily)

### 👉 Always double-check before using



## 🧠 Pro Tips

* Use mv instead of copy+delete
* Avoid rm -rf unless necessary
* Always check path before deleting



## 🚀 Summary

* cp → copy
* mv → move/rename
* rm → delete