# CLI To-Do List Manager

## INTRODUCTION 
To design a simple console based Python program that helps users manage daily tasks including viewing, adding, and deleting tasks dynamically. <br>
**name :** Dhirendra kumar thakur <br>
**reg no. :** 25BAI10251

## Overview
The CLI To-Do List Manager is a lightweight, terminal-based application designed to help users organize their day-to-day tasks. It allows users to view, add, and delete tasks efficiently. The application includes data persistence, meaning tasks are saved to a text file and retrieved automatically upon restarting the program.

## Features
* **Task Management:** Add new tasks and remove completed ones.<br>
* **Data Persistence:** Automatically saves tasks to `todo_list.txt` so data is never lost.<br>
* **Input Validation:** Prevents empty entries and handles invalid numeric inputs gracefully.<br>
* **User-Friendly Interface:** clear numbered lists and an intuitive menu loop.

## Technologies/Tools Used
* **Language:** Python 3.x
* **Modules:** `os` (Standard Library) for file handling.
* **Editor:** VS Code / IDLE / Any Text Editor.

## Steps to Install & Run
1.  **Prerequisites:** Ensure you have Python installed on your system. You can check by running `python --version` in your terminal.<br>
2.  **Download:** Download the `main.py` file to a local directory.<br>
3.  **Run:** Open your terminal or command prompt, navigate to the directory, and run:
    ```bash
    python main.py
    ```
    <br>
4.  **Data File:** On the first run, the program will automatically create a `todo_list.txt` file in the same folder to store your tasks.

## Instructions for Testing
1.  **Start the App:** Run the script.<br>
2.  **Add a Task:** Select option `2`, type "Buy Groceries", and press Enter. Verify it says "Task added!".<br>
3.  **Verify Persistence:** Select option `4` to exit. Run the script again. Select option `1` to view tasks. "Buy Groceries" should still be there.<br>
4.  **Delete a Task:** Select option `3`. Enter the number corresponding to "Buy Groceries". Verify it is removed.<br>
5.  **Error Handling:** Try to delete a task using a letter (e.g., "a") or a number that doesn't exist. Verify the program catches the error and does not crash.<br>
