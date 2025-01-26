# Linux Commands - Basic Cheat Sheet 🐧
![image](https://github.com/user-attachments/assets/f9130133-9cc3-4576-936e-e9fce58e50b1)

## Navigation and Information 🧭

| Command       | Function / Explanation                                         |
|---------------|----------------------------------------------------------------|
| `pwd`         | Prints the current working directory.                          |
| `cd`          | Changes the directory to the specified path.                  |
| `cd ..`       | Moves up one level to the parent directory.                   |
| `ls`          | Lists the contents of the current directory.                  |
| `whoami`      | Displays the current user's username.                         |
| `cd ~`        | Navigates to the home directory.                              |
| `clear`       | Clears the terminal screen.                                   |
| `man [command]`| Displays the manual page for a command (e.g., `man ls`).      |
| `uname -a`    | Shows system information, including the kernel version.       |
| `history`     | Displays a list of previously executed commands.              |

## File Management 🗃️

| Command       | Function / Explanation                                         |
|---------------|----------------------------------------------------------------|
| `mkdir`       | Creates a new directory.                                      |
| `touch`       | Creates a new empty file.                                     |
| `cat`         | Displays the contents of a file.                              |
| `echo`        | Prints text or variables to the terminal.                     |
| `nano`        | Opens a file in the nano text editor.                         |
| `rm`          | Removes a specified file.                                     |
| `rm -ri`      | Removes a directory with confirmation prompts.                |


## Bash Scripting Basics 🚀  

| Command / Syntax        | Function / Explanation                                                   |  
|--------------------------|-------------------------------------------------------------------------|  
| `#!/bin/bash`            | Shebang: Specifies the interpreter (in this case, Bash) for the script. |  
| `bash [scriptname.sh]`   | Runs a script using the Bash interpreter.                               |  
| `chmod +x [scriptname.sh]`| Makes a script executable so it can be run with `./scriptname.sh`.      |  
| `echo`                   | Prints text or variables to the terminal (e.g., `echo "Hello World!"`). |  
| `read`                   | Reads input from the user (e.g., `read name`).                          |  
| `$1`, `$2`, ...          | Positional arguments passed to the script (e.g., `./script.sh arg1`).    |  
| `$(command)`             | Command substitution: Runs a command and uses its output (e.g., `user=$(whoami)`). |  
| `sleep [seconds]`        | Pauses script execution for a specified number of seconds.              |  

---

