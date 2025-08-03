### 0-alias
Creates an alias named `ls` that runs `rm *`. When sourced, typing `ls` will delete all files in the current directory.
### 1-hello_you
Prints `hello <user>`, where `<user>` is the current Linux user, using the `$USER` environment variable.
### 2-path
Appends `/action` to the end of the `PATH` environment variable, making it the last directory the shell searches for executables.
### 3-paths
Counts the number of directories in the PATH environment variable by converting it to lines and counting them.
### 4-global_variables
Lists all environment (global) variables using the `printenv` command.
### 5-local_variables
Uses the `set` built-in to list all local variables, environment variables, and shell functions.
### 6-create_local_variable
Creates a local variable named `BEST` and assigns it the value `School`.
### 7-create_global_variable
Creates a global environment variable named `BEST` with the value `School` using `export`.
### 8-true_knowledge
Prints the result of adding 128 to the value stored in the environment variable `TRUEKNOWLEDGE`.
### 9-divide_and_rule
Prints the result of dividing the environment variable `POWER` by `DIVIDE`.
### 10-love_exponent_breath
Prints the result of raising the environment variable `BREATH` to the power of `LOVE`.
### 11-binary_to_decimal
Converts the binary number stored in the environment variable `BINARY` to its decimal equivalent using Bash's base conversion syntax.
### 12-print_combinations
Prints all two-letter combinations from a to z, excluding "oo", in alphabetical order.
### 13-print_float
Prints the value of the environment variable `NUM` formatted with two decimal places.
### 14-decimal_to_hexadecimal
This script converts a number from base 10 to base 16 (hexadecimal). The input number is expected to be stored in the environment variable DECIMAL.
### `15-rot13`

**Description:**
This script encodes or decodes text using the ROT13 cipher. It reads input from standard input and outputs the transformed text.

**Usage Example:**
```bash
echo "Hello" | ./15-rot13
# Output: Uryyb

### `16-odd`

**Description:**
This script prints every other line from input, starting with the first (i.e., lines 1, 3, 5, ...).

**Usage Example:**
```bash
cat file.txt | ./16-odd

### `17-water_and_stir`

**Description:**
This script adds two numbers stored in the environment variables `WATER` and `STIR`, interpreting them from custom bases (`$water` and `$stir`), and prints the result in base `$bestchol`.

**Usage Example:**
```bash
export WATER=A1
export STIR=11
export water=16
export stir=10
export bestchol=16
./17-water_and_stir
# Output: B2