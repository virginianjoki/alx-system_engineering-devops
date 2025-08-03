 0x03. Shell, init files, variables and expansions

 Description
This project focuses on **Bash shell variables**, **initialization files**, **expansions**, **shell arithmetic**, and the **alias** command.  
The goal is to understand how environment and local variables work, how to manipulate them, and how to perform arithmetic and text transformations directly in the shell.

---

 Learning Objectives
By the end of this project, you should be able to explain:
- What happens when you type a command with expansions like `ls -l *.txt`
- The role of `/etc/profile`, `/etc/profile.d`, and `~/.bashrc`
- The difference between local and global variables
- What reserved variables are and how to use them
- How to create, update, and delete variables
- Special shell parameters and their purposes
- How to use single vs double quotes
- Command substitution with `$(...)` and backticks
- How to perform shell arithmetic
- Creating and managing aliases
- Running commands from a file in the current shell

---

## Project Requirements
- All scripts tested on **Ubuntu 20.04 LTS**
- Exactly **two lines per script**
- First line must be `#!/bin/bash`
- End each file with a new line
- No use of `&&`, `||`, `;`
- No use of `bc`, `sed`, or `awk`
- All files must be executable

---

## Files & Tasks

| File | Description |
|------|-------------|
| `0-alias` | Creates an alias `ls` that runs `rm *` |
| `1-hello_you` | Prints "hello user", where `user` is the current Linux user |
| `2-path` | Adds `/action` to the end of the `PATH` variable |
| `3-paths` | Counts the number of directories in the `PATH` |
| `4-global_variables` | Lists environment variables |
| `5-local_variables` | Lists all local and environment variables, and shell functions |
| `6-create_local_variable` | Creates a new local variable `BEST="School"` |
| `7-create_global_variable` | Creates a new global variable `BEST="School"` |
| `8-true_knowledge` | Prints the result of adding `128` to `$TRUEKNOWLEDGE` |
| `9-divide_and_rule` | Prints the result of `$POWER` divided by `$DIVIDE` |
| `10-love_exponent_breath` | Displays `$BREATH` raised to the power of `$LOVE` |
| `11-binary_to_decimal` | Converts the binary number in `$BINARY` to decimal |
| `12-com
