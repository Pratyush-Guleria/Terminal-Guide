# ✏️ Editing Files in Terminal

Editing files means creating or modifying content inside files using terminal tools.


## 🧠 Basic Concept

In terminal, we don’t always use GUI editors.
We use command-line editors like:

- nano (beginner-friendly)
- vim (advanced)


## 📌 1. nano (Easy Editor)

#### 👉 Open or create file

```bash
nano file.txt
```

#### 👉 Write content

Just start typing

#### 👉 Save file

Press:
CTRL + O → Enter

#### 👉 Exit nano

Press:
CTRL + X

## 📌 2. vim (Advanced Editor)

#### 👉 Open file

```bash 
vim file.txt
```

#### 👉 Modes in vim

* Normal mode (default)
* Insert mode (press i)
* Command mode (press ESC)

#### 👉 Write content

Press i → start typing

#### 👉 Save & Exit

Press ESC, then type:

```bash 
:wq
```

## ⚠️ Common Mistakes

❌ Forgetting to save before exit
❌ Getting stuck in vim (not knowing how to exit 😭)

#### 👉 Exit vim without saving:

```bash 
:q!
```

## 🧠 Pro Tips

* Use nano if you are beginner
* Learn vim slowly (very powerful)
* Always double-check before saving important files


## 🚀 Summary

* nano → easy & beginner friendly
* vim → powerful but complex
* Editing files is an essential terminal skill