# Mission 2 — Become Comfortable with the Terminal

## 1. Mission Title
Become Comfortable with the Terminal

## 2. Task / Objective
Practise command-line operations, manage files and folders, understand command flags and pipes, and explore package managers.

## 3. Work Completed

### Task 2.1 — Basic Terminal Operations

| Operation | Command | Purpose |
|---|---|---|
| Current directory | pwd | Displays the current folder path |
| Directory listing | ls | Lists files and folders |
| Detailed listing | ls -l | Displays detailed information |
| Change directory | cd .. | Moves to the parent folder |
| Create directory | mkdir | Creates a folder |
| Create empty file | touch | Creates an empty file |
| Copy file | cp | Creates a copy of a file |
| Rename / Move | mv | Renames or moves a file |
| Display contents | cat | Displays file contents |

### Task 2.2 — File Management

Created a folder named `terminal-practice` and practised creating, editing, copying and renaming files.

Commands used:

- `touch notes.txt` – Creates an empty text file.
- `echo "text" > notes.txt` – Writes text and replaces existing contents.
- `echo "text" >> notes.txt` – Adds text without removing previous contents.
- `cat notes.txt` – Displays file contents.
- `cp notes.txt backup.txt` – Creates a backup copy.
- `mv backup.txt final_backup.txt` – Renames the backup file.

**Answers:**

1. Replacing vs appending: Replacing removes the previous contents and writes new text, while appending adds text at the end without deleting existing contents.

2. Copying vs moving: Copying creates another version of a file, while moving changes its location or name.

3. Current-directory display: It tells us the exact location of the folder where we are currently working.

4. Directory listing: It helps us see the files and folders available in the current location.

### Task 2.3 — Flags and Pipes

Flags modify the behaviour of commands.

- `-l` – Displays detailed file information.
- `-a` – Includes hidden files.
- `-h` – Displays file sizes in a human-readable format.

The command `ls -lah` combines these three options.

A pipe (`|`) sends the output of one command to another command.

Example:

`ls -l | head -5`

Here, `ls -l` displays detailed file information, while `head -5` displays only the first five lines.

### Task 2.4 — Package Managers

A package manager is a tool that helps install, update and remove software.

Homebrew is a commonly used package manager on macOS. It helps manage software packages and their dependencies, making software installation and updates easier.

Homebrew installation status: [Fill in your actual result from brew --version].

## 4. Commands / Tools Used

- pwd – Displays current directory.
- ls – Lists files and folders.
- ls -l – Displays detailed information.
- cd – Changes directory.
- mkdir – Creates folders.
- touch – Creates files.
- cp – Copies files.
- mv – Moves or renames files.
- cat – Displays file contents.
- echo – Writes text into files.
- head – Displays the first few lines.
- brew --version – Checks Homebrew version.
- brew list – Lists installed Homebrew packages.

## 5. My Understanding

I learned how to navigate folders and manage files using Terminal. I understood the difference between replacing and appending text, and between copying and moving files.

I also learned that flags modify command behaviour and pipes connect commands by passing output from one command to another.

Package managers make it easier to install, update and manage software.

## 6. Difficulties Faced
No major difficulties faced.

## 7. How I Resolved Them
Not applicable.

## 8. Evidence / Files
- terminal-practice folder.
- notes.txt.
- renamed.txt.
- final_backup.txt.
- Terminal command outputs.

## 9. Commit Details
Commit message: Complete Terminal and file management mission.

Status: To be committed and pushed.
