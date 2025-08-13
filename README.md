# QBasic Programming Language Compiler

A **QBasic compiler** implementation developed using [JavaCC](https://javacc.github.io/javacc/) (Java Compiler Compiler).  
This project parses and processes QBasic source code, demonstrating lexical analysis, syntax analysis, and basic compilation concepts.

---

## 📌 Overview

This project is an educational implementation of a **QBasic compiler**.  
It takes QBasic source code as input, parses it using grammar rules defined in JavaCC,  
and produces an intermediate representation or error messages for incorrect syntax.

**Key points:**

- Developed with **JavaCC** for lexical and syntax parsing.
- Written in **Java**.
- Designed to demonstrate **compiler design principles** for a classic BASIC dialect.
- The main entry point is `CodeParser.java` located in the `src` folder.

---

## 🛠 Features

- **Lexical Analysis**  
  Tokenizes QBasic source code into keywords, identifiers, literals, and operators.

- **Syntax Analysis**  
  Parses QBasic programs based on grammar rules to check for correctness.

- **Error Handling**  
  Provides meaningful error messages for incorrect syntax.

- **Modular Design**  
  Grammar definitions and parser logic are organized for easy modification.

---

## 📂 Project Structure
