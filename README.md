# 🐚 Learning Bash Script From Zero To Hero

### ⚙️ **Language:** `Bash Script` | 📜 **License:** [`MIT`](./LICENSE) | ⏳ **Status:** `In Progress`

An educational repository dedicated to compiling, summarizing, and documenting the **Bash Scripting Course Tutorial**. This project serves as a quick, simplified reference for developers and system engineers looking to master task automation in Linux/Unix environments from scratch.

📌 **Original Course Playlist:** [Bash Scripting Course Tutorial on YouTube](https://www.youtube.com/playlist?list=PLBdyyeW_Z41DykncH9zzMk8T7Rm5UlZXd)

---

## 📂 Repository Contents & Architecture

To make the learning process clear, the repository is split into two functional parts inside the `Data/` directory:

* 📜 [notes.sh](./Data/notes.sh) — **The Ultimate Study Guide**  
  An all-in-one structured file containing the clean, documented explanations of the concepts, fully annotated with step-by-step comments.
  
* 🧪 [bash.sh](./Data/bash.sh) — **The Live Playground & Sandbox**  
  The actual hands-on testing file containing **1,700+ lines of live testing code** where snippets are written and verified in real-time. Successful test blocks are commented out safely to preserve working examples.

---

## 📖 Core Concepts Covered So Far (Videos 1 - 24)

Inside the `bash.sh` playground, the following milestones have been successfully implemented and tested:

* 🚀 **01 - 04 | Foundations & Variables:** Terminal emulation, Shebang environment setups, text formatting via `echo -e`, variable constraints, and positional parameters (`$0`, `$1`, `$#`).
* 🔐 **05 | Interactive Inputs:** Dynamic user capture using `read` flags (`-p` prompts, `-s` silent modes, timeouts `-t`, and array inputs `-a`).
* 🧮 **06 - 10 | Arithmetic Operators:** Mathematical evaluations using `$(( ))`, command-line evaluation with `expr`, text manipulation (`length`, `index`, `substr`, `match`), logic gates (`AND`/`OR`), floating-point work via `python3`/`awk`, and variable stepping with `let`.
* 🔀 **11 - 15 | Control Flow (If Statements):** Advanced comparisons (`-eq`, `-ne`, `-gt`, `-lt`), multi-conditional expressions (`&&`, `||`, `!`), and full system file-testing flags (`-d`, `-e`, `-s`, `-r`, `-w`, `-x`, `-f`).
* 🧩 **16 - 20 | Regular Expressions (Regex Masterclass):** Complete syntax deep-dive alongside successfully verified challenge solutions from **RegexOne** (including decimals, phone numbers, emails, HTML tags, and URL parsers).
* 🧵 **21 - 22 | String Comparisons:** Pattern matching, empty-string checking via `-z`/`-n`, and alphabetical sorting evaluations (`>` / `<`).
* 🎛️ **23 - 24 | Case Statements:** Implementing clean decision multi-branch structures, file compression handlers (`*.tar`, `*.zip`), and execution fall-through operators (`;;`, `;&`, and `;;&`).

---

## 📅 Upcoming Topics (To-Do List: Videos 25 - 50)

The remaining roadmap to complete the course curriculum will cover the following advanced subjects:

- [ ] 🔄 **Videos 25 - 27 | For Loop:** Mastering sequence generation, file loops, and nested iterations.
- [ ] 🔄 **Videos 28 - 29 | While Loop:** Advanced conditional loops and reading files line-by-line.
- [ ] 🔄 **Video 30 | Until Loop:** Reversing loop logic based on false conditions.
- [ ] 📦 **Videos 31 - 36 | Arrays:** Defining, indexing, updating, and iterating over continuous data arrays.
- [ ] 🛠️ **Videos 37 - 40 | Functions:** Encapsulating reusable logic, passing local parameters, and handling return values.
- [ ] 🌐 **Video 41 | Variable Scopes:** Understanding the core differences between `local`, `export`, and `default` scope levels.
- [ ] 🛑 **Video 42 | Exit Codes:** Handling script termination states and structural error handling.
- [ ] ⚙️ **Videos 43 - 44 | Internal Variables:** Deep-dive into standard automation variables.
- [ ] 🎛️ **Video 45 | Select Keyword:** Creating interactive CLI menus for users easily.
- [ ] 🧠 **Video 46 | Eval:** Dynamic command execution and argument parsing.
- [ ] 🔧 **Video 47 | Getopts & Shift:** Parsing custom command-line flags and script parameters.
- [ ] 🔒 **Video 48 | Declare:** Enforcing strict data-types and read-only attributes on variables.
- [ ] 🧪 **Video 49 | Practical Lab:** Comprehensive real-world script consolidation.
- [ ] 🚩 **Video 50 | TryHackMe Challenge:** Applying final skills on dynamic cyber-security labs.

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

## 📱 Connect With Me

If you have any questions or want to follow my learning journey, feel free to connect:
* **GitHub:** [@crypt1cx01](https://github.com/crypt1cx01)

---

## 📜 Disclaimer

💡 **Note:** All intellectual property and video contents belong to the original channel creator on YouTube. This repository is a personal initiative for documentation, summarization, and study purposes to help the developer community.
