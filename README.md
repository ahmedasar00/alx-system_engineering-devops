# ALX System Engineering - Shell Variables & Expansions

This repository contains all exercises from the **0x03 Shell Variables & Expansions** project. The tasks cover environment variables, arithmetic operations, string manipulation, conversions between number bases, ROT13 encryption, and custom base calculations in Bash.

## Table of Contents

- [Tasks Overview](#tasks-overview)
- [Scripts](#scripts)
- [Usage](#usage)
- [Requirements](#requirements)
- [Author](#author)

## Resources

- [The Linux Documentation Project – Bash Beginner’s Guide](https://tldp.org/LDP/Bash-Beginners-Guide/html/sect_03_01.html)
- [Linfo.org – alias command explanation](https://www.linfo.org/alias.html)
- [GNU Bash Manual – Shell Arithmetic Expansion](https://www.gnu.org/software/bash/manual/html_node/Shell-Arithmetic.html)
- [LinuxCommand.org – Learning the shell](https://linuxcommand.org/lc3_lts0080.php)

- [Bash Beginner’s Guide – Chapter 3: Variables](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/misc/2021/6/9112669886fd446a2aa3113c31319d1f468dc160.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20251106%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20251106T003528Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=c11ee77a5005e39a73c3a793a920e6e863c5108fdeefa7abf74a040ddb00569b)

## Tasks Overview

1. **0-alias** - Create an alias named `ls` that displays files in color.
2. **1-hello_you** - Print "hello user", using the `$USER` variable.
3. **2-path** - Add `/action` to the `PATH` environment variable.
4. **3-paths** - List directories in `$PATH`, one per line.
5. **4-global_variables** - Modify a global variable and print its value.
6. **5-local_variables** - Work with local variables inside a function.
7. **6-create_local_variable** - Create a local variable inside a function and print it.
8. **7-create_global_variable** - Create a global variable inside a function and print it.
9. **8-true_knowledge** - Demonstrate variable scope and local/global effects.
10. **9-divide_and_rule** - Divide two numbers using environment variables.
11. **10-love_exponent_breath** - Raise `BREATH` to the power `LOVE`.
    ```bash
    export BREATH=4
    export LOVE=3
    ./10-love_exponent_breath  # Output: 64
    ```
12. **11-binary_to_decimal** - Convert a binary number in `$BINARY` to decimal.
    ```bash
    export BINARY=10100111001
    ./11-binary_to_decimal  # Output: 1337
    ```
13. **12-combinations** - Print all two-letter combinations (a-z), except `oo`.
    ```bash
    ./12-combinations
    ```
14. **13-print_float** - Print a number stored in `$NUM` with two decimal places.
    ```bash
    export NUM=3.141592
    ./13-print_float  # Output: 3.14
    ```
15. **100-decimal_to_hexadecimal** - Convert `$DECIMAL` from base 10 to base 16.
    ```bash
    export DECIMAL=1337
    ./100-decimal_to_hexadecimal  # Output: 539
    ```
16. **101-rot13** - Encode/decode text using ROT13.
    ```bash
    ./101-rot13 < quote
    ```
17. **102-odd** - Print odd numbers from 1 to 100.
18. **103-water_and_stir** - Add two numbers from custom bases (`WATER` and `STIR`) and output in `bestchol` base.
    ```bash
    export WATER="ewwatratewa"
    export STIR="ti.itirtrtr"
    ./103-water_and_stir  # Output: shtbeolhc
    ```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/ahmedasar00/alx-system_engineering-devops.git
cd alx-system_engineering-devops/0x03-shell_variables_expansions
```
