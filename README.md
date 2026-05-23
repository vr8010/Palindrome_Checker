# 🔄 Palindrome Checker

A simple and efficient Python program to check whether a given string or number is a **Palindrome** or not.

A palindrome reads the same forward and backward.

Examples:
- `madam` → ✅ Palindrome
- `racecar` → ✅ Palindrome
- `hello` → ❌ Not a Palindrome
- `121` → ✅ Palindrome

---

## 🚀 Features

- Check strings and numbers
- Case insensitive comparison
- Handles spaces and special characters (if implemented)
- Beginner-friendly Python project
- Fast and lightweight

---

## 📂 Project Structure

```bash
Palindrome_Checker/
│── palindrome.py      # Main palindrome checker logic
│── README.md          # Project documentation
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/vr8010/Palindrome_Checker.git
```

Move into project folder:

```bash
cd Palindrome_Checker
```

Run the script:

```bash
python palindrome.py
```

---

## 💻 Usage Example

Input:

```bash
Enter text: Madam
```

Output:

```bash
Palindrome ✅
```

Input:

```bash
Enter text: Python
```

Output:

```bash
Not a Palindrome ❌
```

---

## 🧠 How It Works

The program:

1. Takes user input
2. Reverses the input string
3. Compares original and reversed values
4. Returns palindrome status

Example logic:

```python
text = input("Enter text: ")

if text == text[::-1]:
    print("Palindrome")
else:
    print("Not Palindrome")
```

---






## 🎯 Learning Outcomes

This project helps understand:

- String manipulation
- Slicing in Python
- Conditional statements
- Basic algorithm implementation

---

## 🔥 Future Improvements

- GUI version (Tkinter)
- Web version using Flask
- Ignore punctuation automatically
- Support sentence palindrome checking

---

## 🤝 Contributing

Contributions are welcome.

1. Fork repository
2. Create new branch
3. Commit changes
4. Open Pull Request

---

## 👨‍💻 Author
Vishal Rathod

**Vishal Rathod**

GitHub: :contentReference[oaicite:0]{index=0}
