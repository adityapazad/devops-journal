# Process & System Monitoring

## Process
A process is a program that is currently running on the system. When a command executes in linux, the OS creates a process to run that command.

## Process can be run in two ways:

### 1. Foreground Process
A process that run in the terminal and takes input/output directly from the user.
- Runs in the terminal by default.
- Blocks the terminal untill it finishes
- Takes input from keyboard
- Sends output to the screen

### 2. Background Process
A process that runs without blocking the terminal, allowing you to execute other commands.
- Keyboard input is not required while running
- Add '&' at the end of the command to start a process in the background

## Commands
- `ps` : display a snapshot of currently running processes
- `top` : shows live, continuosly updating system processes
- `htop` : interactive and improved version of 'top'
- `kill` : sends a signal to terminate a process using its PID
- `kill -9` : forcefully terminates a process
- `&` : runs a command in the background
- `jobs` : list background jobs running in the current shell
