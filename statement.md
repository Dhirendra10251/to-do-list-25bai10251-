## Problem Statement
In a fast-paced digital environment, users often get overwhelmed by complex productivity apps with too many features. 

There is a need for a minimalist, distraction-free tool that allows users to quickly jot down and manage tasks directly from their developer environment (the terminal) without needing to open a web browser or heavy GUI application.

## Scope of the Project

The project is limited to a Command Line Interface (CLI). It focuses on the core "CRUD" (Create, Read, Delete) functionalities.<br>

**In Scope:** Adding tasks, listing tasks, deleting tasks by index, saving data to a local text file. <br>

**Out of Scope:** Graphical User Interface (GUI), deadlines/reminders, user authentication, or cloud synchronization.

## Target Users
1.**Developers & Sysadmins:** Users who prefer staying in the terminal environment.<br>

2.**Students:** Those learning Python and file handling basics.<br>

3.**Minimalists:** Users seeking a lightweight alternative to complex project management software.

## High-Level Features
1. **Menu System:** A continuous loop allowing the user to perform multiple actions without restarting the script.

2. **File I/O:** capability to read from and write to a `.txt` file to ensure tasks persist between sessions.

3. **Error Checking:** Logic to ensure users cannot crash the program by entering invalid integers or empty strings.
