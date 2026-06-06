# 🐚 Learning Bash Script From Zero To Hero

### ⚙️ **Language:** `Bash Script` | 📜 **License:** `MIT` | ⏳ **Status:** `In Progress`

An educational repository dedicated to compiling, summarizing, and documenting the **Bash Scripting Course Tutorial**. This project serves as a quick, simplified reference for developers and system engineers looking to master task automation in Linux/Unix environments from scratch.

📌 **Original Course Playlist:** [Bash Scripting Course Tutorial on YouTube](https://youtube.com)

---

## 📂 Repository Contents & Architecture

To make the learning process clear, the repository is split into two functional parts inside the `Data/` directory:

* 📜 [notes.sh](./Data/notes.sh) — **The Ultimate Study Guide**  
  An all-in-one structured file containing the clean, documented explanations of the concepts, fully annotated with step-by-step comments.
  
* 🧪 [bash.sh](./Data/bash.sh) — **The Live Playground & Sandbox**  
  The actual hands-on testing file where code snippets are written and verified in real-time. Successful test blocks are commented out safely to preserve working examples.

---

## 📖 Core Concepts Covered So Far

Inside these files, you will find practical applications and explanations of:
* 🚀 **Foundations:** Setting up the Shebang (`#!/bin/bash`) and printing terminal outputs using `echo`.
* 📦 **Variables:** Defining and invoking custom dynamic values correctly using the `$` syntax.
* 🔐 **Interactive Inputs:** Capturing user inputs via `read -p` and handling masked data like passwords with `read -s`.
* 🔀 **Control Flow:** Building decision-making logic using conditional structures (`if`, `elif`, `else`, `fi`).
* 🔄 **Automation Loops:** Writing persistent automated tests and script iterations using the `while` loop.

---

## 📅 Upcoming Topics (To-Do List)

As the course progresses, the following advanced topics will be covered and added to the repository:
- [ ] Advanced Arrays & Associative Arrays
- [ ] Functions & Variable Scope (`local` vs `global`)
- [ ] Regular Expressions (Regex) in Bash
- [ ] Advanced Text Processing (`sed` & `awk`)
- [ ] Error Handling and Debugging Scripts (`set -x`, `set -e`)

---

## 🛠️ Recommended Environment

For the best experience writing and testing these scripts, it is highly recommended to use:
* 💻 **OS:** Linux (Ubuntu/Debian) or macOS. *(Windows users can use **WSL2** or **Git Bash**)*.
* 📝 **Editor:** **VS Code** with the **ShellCheck** extension installed to detect syntax errors automatically.

---

## ⚡ Quick Start & Execution

To explore the playground or run the notes on your local machine, open your terminal and execute:

```bash
# 1. Clone the project to your machine
git clone https://github.com

# 2. Enter the data directory
cd _BASH_/Data

# 3. Give execution permission and run your file of choice
chmod +x notes.sh bash.sh

# Run the playground to see live tests:
./bash.sh
```

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create! Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingNotes`)
3. Commit your Changes (`git commit -m 'Add some AmazingNotes'`)
4. Push to the Branch (`git push origin feature/AmazingNotes`)
5. Open a Pull Request

---

## 📜 Disclaimer

💡 **Note:** All intellectual property and video contents belong to the original channel creator on YouTube. This repository is a personal initiative for documentation, summarization, and study purposes to help the developer community.
