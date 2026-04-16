# 👀 Viewing File Content

## 🔹 Why is this important?

👉 Terminal me kaam karte waqt hamesha file open nahi karte  
👉 Direct terminal se content dekhte hain

---

## 🔹 cat (Concatenate)

👉 File ka content show karta hai

```bash
cat file.txt
```

## 🔹 less

👉 Large file ko scroll karke dekhne ke liye

```bash 
less file.txt
```
### Controls:
	•	q → exit
	•	↑ ↓ → scroll

⸻

## 🔹 head

👉 File ke first lines show karta hai

```bash 
head file.txt
```
👉 Default: first 10 lines


## 🔹 tail

👉 File ke last lines show karta hai

```bash 
tail file.txt
```
👉 Real use:

```bash 
tail -f logs.txt
```
👉 Live logs dekhne ke liye 🔥

## 🧠 Real Use Case
	•	Debug logs → tail -f
	•	Quick view → cat
	•	Large file → less

⸻

## 🚀 Summary
	•	cat → full content
	•	less → scroll view
	•	head → starting lines
	•	tail → ending lines