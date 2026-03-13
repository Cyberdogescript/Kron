# Kron Programming Language

Kron is an experimental lightweight programming language with a custom interpreter, standard libraries, and editor support.

The project is designed as a simple and extensible scripting language that demonstrates how programming languages, interpreters, and tooling can be built from scratch.

---

## Features

* Custom Kron interpreter
* Standard libraries (math, http, sorting, file operations, strings)
* Command-line runtime (`kron file.krn`)
* Syntax highlighting for Visual Studio Code and Notepad++
* Snippets and basic IDE support
* Simple and readable syntax

---

## Example Code

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

## Project Structure

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
│   └ filelib.py
│
├ examples/
│   └ main.krn
│
└ vscode-extension/
```

---

## Installation

### 1. Clone the repository

```
git clone https://github.com/yourname/kron
cd kron
```

### 2. Run Kron

```
kron main.krn
```

or directly using Python:

```
python runtime/kron.py main.krn
```

---

## Command Line Usage

```
kron file.krn       Run Kron script
kron --help         Show help
kron --version      Show Kron version
```

---

## Standard Libraries

Kron includes several built-in libraries:

| Library | Description          |
| ------- | -------------------- |
| math    | math operations      |
| http    | HTTP requests        |
| sort    | sorting algorithms   |
| string  | string utilities     |
| file    | file operations      |
| random  | random numbers       |
| time    | time functions       |
| json    | JSON utilities       |
| net     | networking utilities |
| console | console utilities    |

Example:

```
x = math.add(5,7)
http.get("https://example.com")
sort.stalin([5,3,7,4,9])
```

---

## Editor Support

Kron currently provides:

* Syntax highlighting for **Visual Studio Code**
* Syntax highlighting for **Notepad++**
* Code snippets for Kron functions

Planned features:

* IntelliSense / autocomplete
* Debugger
* Formatter

---

## Roadmap

Future improvements for Kron:

* Lexer and parser system
* AST interpreter
* Bytecode virtual machine
* Package manager (`kron install`)
* Project manager (`kron new`)
* Debugging tools
* Full language server support

---

## License

Kron is released under the **MIT License**.

---

## Author

Created by **Bartu**.
