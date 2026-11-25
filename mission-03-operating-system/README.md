# Mission 3 — Understand the Operating System

## 1. Task / Objective
Explore the operating system, running processes, storage, paths and file permissions.

## 2. Work Completed

### Task 3.1 — Operating System Exploration

| Information | What it tells me | Observation |
|---|---|---|
| Operating system | Identifies the OS | macOS Golden Gate 27.2.1 |
| Current account | Identifies the active user | [redacted] |
| Storage | Shows used and available space | [Fill from df -h /] |
| System activity | Shows running system activity | Observed using top |

### Task 3.2 — Processes

A process is a program that is currently running on a computer.

The PID (Process ID) is a unique number assigned to each running process.

Examples:
1. Brave browser
2. Visual Studio Code

### Task 3.3 — Paths and Permissions

An absolute path gives the complete location of a file or folder starting from the root directory.

A relative path describes a location in relation to the current directory.

Example absolute path:
`/Users/[redacted]/Desktop/digital-detective-8423/terminal-practice`

Example relative path:
`terminal-practice/notes.txt`

File permissions:
- r – Read: Allows viewing file contents.
- w – Write: Allows modifying file contents.
- x – Execute: Allows running a file or accessing a directory.

### Task 3.4 — Operating System Responsibilities

| Responsibility | Explanation | Example |
|---|---|---|
| Process management | Manages running programs. | Running multiple applications. |
| Memory management | Allocates RAM to programs. | Giving memory to a browser. |
| Device management | Controls hardware devices. | Managing a keyboard. |
| File management | Organises files and folders. | Creating files. |
| User interface / shell | Allows user interaction. | Desktop and Terminal. |
| Security and permissions | Controls access to resources. | File access permissions. |

## 3. Commands / Tools Used
- sw_vers
- whoami
- df -h /
- top
- ps
- pwd
- cd
- ls -l

## 4. My Understanding
I learned that an operating system manages hardware and software resources. It handles processes, memory, storage, connected devices and security. I also understood the difference between absolute and relative paths and the importance of file permissions.

## 5. Difficulties Faced
[Write any actual difficulty faced.]

## 6. How I Resolved Them
Used Terminal commands to inspect the system and understand its operations.

## 7. Evidence / Files
- System information
- Process listing
- Storage information
- File permissions

## 8. Commit Details
Commit message: Document operating system and file management.
