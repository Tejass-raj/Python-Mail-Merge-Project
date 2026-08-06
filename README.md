# 📧 Mail Merge Automation using Python

A simple yet powerful Python project that automates the process of generating personalized letters using a template. By reading recipient names from a text file and replacing placeholders in a letter template, the program creates customized letters for each recipient automatically.

---

## 📖 Overview

This project demonstrates how Python can automate repetitive document creation tasks through a Mail Merge system. The program reads a list of recipient names from a text file, loads a template letter, replaces the placeholder (`[name]`) with each recipient's name, and generates personalized letters in an output directory.

The project highlights Python's file handling capabilities and string manipulation techniques, making it an excellent beginner-friendly automation project for learning real-world applications of Python.

---

## ✨ Features

- 📄 Reads recipient names from a text file
- ✉️ Generates personalized letters automatically
- 🔄 Replaces placeholders with actual names
- 💾 Saves each letter as a separate file
- 🐍 Simple and efficient Python implementation
- 📂 Organized input and output folder structure

---

## 🛠️ Technologies Used

- Python 3
- File Handling
- String Manipulation

---

## 📂 Project Structure

```
Mail-Merge/
│
├── Input/
│   ├── Letters/
│   │   └── starting_letter.txt
│   └── Names/
│       └── invited_names.txt
│
├── Output/
│   └── ReadyToSend/
│
├── main.py
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Mail-Merge.git
```

2. Navigate to the project folder

```bash
cd Mail-Merge
```

3. Add recipient names to:

```
Input/Names/invited_names.txt
```

4. Edit the letter template:

```
Input/Letters/starting_letter.txt
```

5. Run the program

```bash
python main.py
```

6. Generated personalized letters will be saved in:

```
Output/ReadyToSend/
```

---

## 📚 Concepts Demonstrated

- File Handling
- Reading and Writing Files
- String Replacement
- Loops
- Automation
- Directory Management

---

## 📸 Output

Example generated files:

```
letter_for_Alice.docx
letter_for_John.docx
letter_for_Emma.docx
```

---

## 🔮 Future Improvements

- Support PDF generation
- Email integration
- Custom placeholders (Date, Address, Event)
- CSV and Excel support
- GUI version using Tkinter
- Batch email sending

---

## 👨‍💻 Author

**Tejas Raj**

If you found this project helpful, consider giving it a ⭐ on GitHub!
