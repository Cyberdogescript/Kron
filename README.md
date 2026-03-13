# Kron Programming Language

**Kron** is an experimental lightweight programming language with a custom interpreter, a set of standard libraries, and editor support.

The goal of the project is to demonstrate how a programming language, its interpreter, and development tools can be built from scratch.

Kron currently runs on a Python-based runtime and supports simple scripting, libraries, and command-line execution.

---

# Features

* Custom Kron interpreter
* 20 standard libraries
* Command-line runtime (`kron file.krn`)
* Syntax highlighting for Visual Studio Code
* Syntax highlighting for Notepad++
* Code snippets for Kron
* Simple readable syntax
* Extendable library system

---

# Example Program

```kron
kron 0.1

func main(write, math, http, sort)

write("Start")

x = math.add(5,7)

write(x)

sort.stalin([5,3,7,4,9,2])

end func
```

Output:

```
Start
12
[5, 7, 9]
```

---

# Project Structure

```
Kron/
│
├ bin/
│   └ kron.cmd
│
├ runtime/
│   └ kron.py
│
├ stdlib/
│   ├ mathlib.py
│   ├ httplib.py
│   ├ sortlib.py
│   ├ stringlib.py
│   ├ filelib.py
│   ├ timelib.py
│   ├ randomlib.py
│   ├ arraylib.py
│   ├ syslib.py
│   ├ netlib.py
│   ├ jsonlib.py
│   ├ cryptolib.py
│   ├ threadlib.py
│   ├ processlib.py
│   ├ pathlib.py
│   ├ consolelib.py
│   ├ datelib.py
│   ├ configlib.py
│   ├ parserlib.py
│   └ guilib.py
│
├ examples/
│   └ main.krn
│
└ vscode-extension/
```

---

# Installation

## 1. Clone the repository

```
git clone https://github.com/yourname/kron
cd kron
```

## 2. Run Kron

```
kron main.krn
```

or run the interpreter directly:

```
python runtime/kron.py main.krn
```

---

# Command Line Usage

```
kron file.krn       run Kron script
kron --help         show help
kron --version      show version
```

---

# Standard Libraries

Kron currently includes **20 built-in libraries** located in the `stdlib` directory.

| Library    | Description                   |
| ---------- | ----------------------------- |
| mathlib    | mathematical operations       |
| httplib    | HTTP requests                 |
| sortlib    | sorting algorithms            |
| stringlib  | string manipulation           |
| filelib    | file read/write               |
| timelib    | time utilities                |
| randomlib  | random number generation      |
| arraylib   | array utilities               |
| syslib     | system functions              |
| netlib     | networking utilities          |
| jsonlib    | JSON parsing                  |
| cryptolib  | cryptographic tools           |
| threadlib  | multithreading utilities      |
| processlib | process management            |
| pathlib    | path utilities                |
| consolelib | console utilities             |
| datelib    | date utilities                |
| configlib  | configuration utilities       |
| parserlib  | parsing utilities             |
| guilib     | graphical interface utilities |

Example:

```
x = math.add(5,7)
http.get("https://example.com")
sort.stalin([5,3,7,4,9])
```

---

# Editor Support

Kron currently supports:

* Visual Studio Code syntax highlighting
* Notepad++ syntax highlighting
* Kron code snippets

Planned improvements:

* IntelliSense (autocomplete)
* Debugger support
* Formatter
* Language server

---

# Roadmap

Future improvements planned for Kron:

* Lexer and parser system
* AST interpreter
* Bytecode virtual machine
* Package manager (`kron install`)
* Project manager (`kron new`)
* Debugging tools
* Full IDE support

---

# License

Kron is released under the **MIT License**.

---

# Author

Created by **Bartu**.
