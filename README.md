# Lab 2: Simple Shell and Pipe Implementation

## Overview
This project implements:
- `myshell`: A basic shell with support for command execution, signals, I/O redirection, and process management.
- `mypipe`: A program demonstrating interprocess communication using pipes.

---

## Features

### `myshell`
- **Command Execution**: Supports commands with or without arguments.
- **Signal Commands**:
  - `stop <PID>`: Stop a process (SIGSTOP).
  - `wake <PID>`: Resume a stopped process (SIGCONT).
  - `term <PID>`: Terminate a process (SIGINT).
- **I/O Redirection**: Handle `<`, `>`, and combined redirection.
- **Process Management**:
  - Background processes using `&`.
  - Built-in `cd` command to change directories.
  - Debug mode with `-d` to print process details.

### `mypipe`
- Demonstrates a child process sending a message (`"hello"`) to its parent using a pipe.

---

## Usage - Compile & Run & clean up:

- Compile myshell or mypipe using `Makefile`:
  
  ```bash
  make file_name
  ```
- To compile all, simply write `make`
  
- Run myshell or mypipe using the Terminal:
  ```bash
  ./file_name
  ```
  
- Clean up:
  ```bash
  make clean
  ```
 
