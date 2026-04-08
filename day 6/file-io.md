# Day 06 - File I/O Practice (Linux)

## 📌 Objective

Practice basic file operations using Linux commands:

* Creating files
* Writing and appending content
* Reading file content

---

## 🛠️ Steps Performed

1. Created a new file named `notes.txt`
2. Added initial content using overwrite mode
3. Appended new lines using append mode
4. Used `tee` to write and display content simultaneously
5. Verified full content using `cat`
6. Viewed first few lines using `head`
7. Viewed last few lines using `tail`

---

## 📂 Commands Used

* `touch` → Create a new file
* `>` → Overwrite file content  
(example: echo "Hello World" > notes.txt)

* `>>` → Append content to file  
(example: echo "New Line" >> notes.txt)

* `tee` → Write and display output together  
(example: echo "Line 3" | tee -a notes.txt)

* `cat` → Display full file content  
(example: cat notes.txt)

* `head` → Show beginning of file  
(example: head -n 2 notes.txt)

* `tail` → Show end of file  
(example: tail -n 2 notes.txt)
---

## 📖 Key Learnings

* Difference between overwrite (`>`) and append (`>>`)
* How to use `tee` for simultaneous output and storage
* Efficient ways to read large files using `head` and `tail`
* Importance of command-line file handling in DevOps

---

## 🚀 Conclusion

This exercise helped me understand how to efficiently handle file operations in Linux using basic commands. These skills are essential for managing logs, configurations, and automation tasks in DevOps workflows.

---
