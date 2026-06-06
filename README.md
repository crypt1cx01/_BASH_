# 🐚 Learning Bash Script From Zero To Hero

### ⚙️ **Language:** `Bash Script` | 🛡️ **CI Status:** ![Bash CI](https://github.com) | 📜 **License:** [`MIT`](./LICENSE) | ⏳ **Status:** `In Progress`

An educational repository dedicated to compiling, summarizing, and documenting the **Bash Scripting Course Tutorial**. This project serves as a quick, simplified reference for developers and system engineers looking to master task automation in Linux/Unix environments from scratch.

📌 **Original Course Playlist:** [Bash Scripting Course Tutorial on YouTube](https://youtube.com)

---

## 🔍 Table of Contents
* [📂 Repository Contents & Architecture](#-repository-contents--architecture)
* [🧠 Sandbox & Notes Workflow Strategy](#-sandbox--notes-workflow-strategy)
* [📖 Core Concepts & Code Syntax Covered (Videos 1 - 24)](#-core-concepts--code-syntax-covered-videos-1---24)
* [📅 Upcoming Topics & Syntax Roadmap (Videos 25 - 50)](#-upcoming-topics--code-syntax-to-do-list-videos-25---50)
* [🛠️ Recommended Environment](#%EF%B8%8F-recommended-environment)
* [⚡ Quick Start & Execution](#-quick-start--execution)
* [📱 Connect With Me](#-connect-with-me)

---

## 📂 Repository Contents & Architecture

> [!NOTE]
> All core assets are located inside the organized development directory: `📁 Data/`

* 📜 **[`Data/notes.sh`](./Data/notes.sh)** — **The Ultimate Study Guide**  
  An all-in-one massive reference containing **2,100+ lines of highly detailed explanations**, fully annotated and commented out block-by-block for structural documentation.
  
* 🧪 **[`Data/bash.sh`](./Data/bash.sh)** — **The Live Playground & Sandbox**  
  The actual hands-on testing file containing **1,700+ lines of live execution code** where snippets are written and verified in real-time.

---

## 🧠 Sandbox & Notes Workflow Strategy

To maximize learning retention, this repository utilizes an advanced dual-file development ecosystem:

```text
 💻 [Write Live Code] ──> 🧪 [Execute inside bash.sh] ──> ❌ [Bug? Fix Syntax]
                                     │
                                     ▼ (Success Verified)
 📜 [Stored safely in notes.sh] <── [Comment Block & Annotate]
```

> [!TIP]
> This dynamic approach guarantees that all educational code blocks are pre-verified, structurally commented to prevent execution overlapping, and perfectly optimized for future copy-pasting.

---

## 📖 Core Concepts & Code Syntax Covered (Videos 1 - 24)

Click on any topic arrow below to expand and view its quick-reference code framework compiled from `notes.sh`:

<details>
<summary>🚀 <b>01 - 04 | Foundations & Variables</b></summary>

```bash
#!/bin/bash
echo -e "Text \nFormatting"
my_var="value"       # Custom variables
echo "Args: \$0 \$1 \$#" # Positional parameters & args count
```
</details>

<details>
<summary>🔐 <b>05 | Interactive Inputs</b></summary>

```bash
read -p "Enter target: " target
read -s -t 5 -p "Password (5s timeout): " pass
read -a array_input
```
</details>

<details>
<summary>🧮 <b>06 - 10 | Arithmetic Operators & Text Manipulation</b></summary>

```bash
result=\$(( 10 + 5 ))
expr length "text"    # String length, index, match, substr
let x=x+1             # Variable stepping
# Advanced float calculations via python3 / awk
```
</details>

<details>
<summary>🔀 <b>11 - 15 | Control Flow & File System Tests</b></summary>

```bash
if [ \$age -eq 21 ] && [ \$gpa -ge 80 ]; then ...; fi
if [ -f "file.txt" ] && [ -d "folder" ]; then
    # File flags: -d (dir), -e (exist), -s (not empty), -x (executable)
fi
```
</details>

<details>
<summary>🧩 <b>16 - 20 | Regular Expressions (Regex Masterclass)</b></summary>

```bash
# Deep-dive with RegexOne challenge solutions
[[ "user@email.com" =~ ^[A-Za-z0-9._%+-]+@[A-Za-z0-9.-]+\.[A-Za-z]{2,}\$ ]]
```
</details>

<details>
<summary>🧵 <b>21 - 22 | String Comparisons</b></summary>

```bash
if [ "str1" == "str2" ]; then ...; fi
if [ -z "\$empty_str" ] || [ -n "\$not_empty" ]; then ...; fi
if [[ "a" > "b" ]]; then echo "Alphabetical sort"; fi
```
</details>

<details>
<summary>🎛️ <b>23 - 24 | Case Statements</b></summary>

```bash
case \$file in
    *.tar) tar -xvf \$file ;;
    *.zip) unzip \$file ;& # Fall-through operator
    *) echo "Unknown format" ;;
esac
```
</details>

---

## 📅 Upcoming Topics & Code Syntax (To-Do List: Videos 25 - 50)

Click on any upcoming topic arrow to preview the syntax framework that will be implemented next:

<details>
<summary>🔄 <b>Videos 25 - 27 | For Loop</b></summary>

```bash
for item in 1 2 3; do echo \$item; done
# Or C-style: for ((i=0; i<10; i++)); do ...; done
```
</details>

<details>
<summary>🔄 <b>Videos 28 - 29 | While Loop</b></summary>

```bash
while [ condition ]; do
    # commands
done
```
</details>

<details>
<summary>🔄 <b>Video 30 | Until Loop</b></summary>

```bash
until [ condition ]; do
    # runs until condition becomes true
done
```
</details>

<details>
<summary>📦 <b>Videos 31 - 36 | Arrays & Associative Arrays</b></summary>

```bash
my_array=(val1 val2 val3)
echo \${my_array} # Accessing elements
declare -A assoc_array # Key-Value mapping
```
</details>

<details>
<summary>🛠️ <b>Videos 37 - 40 | Functions</b></summary>

```bash
my_function() {
    echo "Hello \$1" # Passing arguments
}
```
</details>

<details>
<summary>🌐 <b>Video 41 | Variable Scopes</b></summary>

```bash
local my_var="private" # Inside functions
export global_var="public" # Environment-wide
```
</details>

<details>
<summary>🛑 <b>Video 42 | Exit Codes</b></summary>

```bash
if [ error ]; then exit 1; fi
echo \$? # Prints status code of last command
```
</details>

<details>
<summary>⚙️ <b>Videos 43 - 44 | Internal & Environment Variables</b></summary>

```bash
echo \$IFS   # Internal Field Separator
echo \$REPLY # Default read variable
```
</details>

<details>
<summary>🎛️ <b>Video 45 | Select Keyword</b></summary>

```bash
select choice in Option1 Option2; do
    echo "You picked \$choice"
done
```
</details>

<details>
<summary>🧠 <b>Video 46 | Eval Command</b></summary>

```bash
cmd="ls -la"
eval \$cmd # Executes the string as a command
```
</details>

<details>
<summary>🔧 <b>Video 47 | Getopts & Shift Operators</b></summary>

```bash
while getopts "u:p:" opt; do
    case opt in u) user=OPTARG;; esac
done
```
</details>

<details>
<summary>🔒 <b>Video 48 | Declare Command</b></summary>

```bash
declare -r read_only_var="locked"
declare -i integer_var=10
```
</details>

<details>
<summary>🧪 <b>Video 49 | Practical Consolidation Lab</b></summary>

*Consolidating all syntaxes into a unified task automation script.*
</details>

<details>
<summary>🚩 <b>Video 50 | TryHackMe Capstone Challenge</b></summary>

*Applying all structures to capture flags and solve live cybersecurity server labs.*
</details>

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

**Greatly appreciated**! If you want to contribute:
1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingNotes`)
3. Commit your Changes (`git commit -m 'Add some AmazingNotes'`)
4. Push to the Branch (`git push origin feature/AmazingNotes`)
5. Open a Pull Request

---

## 📱 Connect With Me

* **GitHub:** [@crypt1cx01](https://github.com/crypt1cx01)

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](./LICENSE) file for details.

---

## 📜 Disclaimer

💡 **Note:** All intellectual property and video contents belong to the original channel creator on YouTube. This repository is a personal initiative for documentation, summarization, and study purposes to help the developer community.
