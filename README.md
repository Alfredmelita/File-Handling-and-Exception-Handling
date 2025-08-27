

File Modifier Program

This is a simple **Python program** that reads a file, modifies its content, and writes the result into a new file.
It also includes **error handling** to make sure the program doesn’t crash if something goes wrong.

---

##  What it does

*  Reads the content of a file you choose.
*  Converts all text to **UPPERCASE** (you can change this).
*  Saves the modified content into a **new file**.
*  Handles common errors (like if the file doesn’t exist).

---

##  How to use it

1. Make sure you have **Python 3** installed 🐍.
2. Save the code into a file, e.g., `file_modifier.py`.
3. Have a text file ready (e.g., `hello.txt`).
4. Run the program:

```bash
python file_modifier.py
```

5. Enter the name of the file you want to modify.
6. The program will create a **new file** starting with `modified_...`.

---

## 🖥 Example Run

 **Case 1: File exists**

```
 File Modifier Program

Enter the filename to read: hello.txt

 Successfully created 'modified_hello.txt' with modified content.
```

 **Case 2: File doesn’t exist**

```
 File Modifier Program

Enter the filename to read: notfound.txt

 Error: The file 'notfound.txt' was not found.
```

---

##  What you’ll learn (as a beginner)

* How to **read** and **write** files in Python.
* How to use **functions** to organize your code.
* How to handle errors with `try...except`.
* How to automatically generate **new output files**.

