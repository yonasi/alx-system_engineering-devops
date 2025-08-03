# 0x03. Shell, init files, variables and expansions

## Project Description
This project focuses on learning about shell initialization files, local and global variables, variable expansions, shell arithmetic, and text transformations in Bash. All scripts are written in Bash, tested on Ubuntu 20.04 LTS, and conform to strict project constraints (2-line scripts, no use of `&&`, `||`, `;`, `bc`, `sed`, or `awk` unless allowed).

## Scripts Description

| File | Description |
|------|-------------|
| `0-alias` | Creates an alias named `ls` with value `rm *` |
| `1-hello_you` | Prints `hello user`, where user is the current Linux user |
| `2-path` | Adds `/action` to the `PATH` environment variable |
| `3-paths` | Counts the number of directories in the current `PATH` |
| `4-global_variables` | Lists all global (environment) variables |
| `5-local_variables` | Lists all local variables, environment variables, and shell functions |
| `6-create_local_variable` | Creates a local variable named `BEST` with value `School` |
| `7-create_global_variable` | Creates a global variable named `BEST` with value `School` |
| `8-true_knowledge` | Adds 128 to the value stored in the `TRUEKNOWLEDGE` environment variable |
| `9-divide_and_rule` | Divides the value of `POWER` by `DIVIDE` environment variables |
| `10-love_exponent_breath` | Raises `BREATH` to the power of `LOVE` environment variables |
| `11-binary_to_decimal` | Converts a binary number stored in `BINARY` to decimal |
| `12-combinations` | Prints all possible two-letter combinations (except `oo`) |
| `13-print_float` | Prints a number stored in `NUM` with two decimal places |
| `100-decimal_to_hexadecimal` | Converts a decimal number stored in `DECIMAL` to hexadecimal |
| `101-rot13` | Encodes and decodes input using ROT13 encryption |
| `102-odd` | Prints every other line from input, starting with the first |

## Requirements
- Bash scripts must be exactly 2 lines long
- First line must be `#!/bin/bash`
- No use of `&&`, `||`, `;` operators
- Scripts must be executable
- Tested on Ubuntu 20.04 LTS

---

## Usage
```bash
# Make a script executable
chmod +x <script_name>

# Run a script
./<script_name>