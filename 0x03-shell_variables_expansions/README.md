0x03-shell_variables_expansions
This project contains shell scripts that demonstrate the use of shell variables, expansions, and basic shell commands in Bash on Ubuntu 20.04 LTS. Each script is exactly two lines long (including the shebang) and is executable.
Scripts Description

0-alias: Creates an alias named ls with the value rm *, which replaces the ls command with rm *.
1-hello_you: Prints "hello" followed by the current Linux user's username, using the $USER environment variable.
2-path: Appends the /action directory to the end of the PATH environment variable.
3-paths: Counts and displays the number of directories in the PATH environment variable by converting colons to newlines and counting lines.
4-global_variables: Lists all environment variables using the printenv command.
5-local_variables: Lists all local variables, environment variables, and functions using the set command.
6-create_local_variable: Creates a local variable named BEST with the value School.
7-create_global_variable: Creates a global (environment) variable named BEST with the value School using export.
8-true_knowledge: Adds 128 to the value of the environment variable TRUEKNOWLEDGE and prints the result.
9-divide_and_rule: Divides the value of the environment variable POWER by DIVIDE and prints the result.
10-love_exponent_breath: Raises the value of the environment variable BREATH to the power of LOVE and prints the result.
11-binary_to_decimal: Converts a binary number stored in the environment variable BINARY to decimal and prints the result.
12-combinations: Prints all possible combinations of two lowercase letters (from aa to zz), excluding oo, in alphabetical order.
13-print_float: Prints the value of the environment variable NUM formatted to two decimal places.

Each script adheres to the project requirements: no use of &&, ||, ;, bc, sed, or awk, and all files are executable with a newline at the end.
