# Pycharm : 

1. Installation and Setup

Download: PyCharm Downloads

Versions:

- Community Edition (Free): Good for basic Python development.
- Professional Edition (Paid): Includes support for web frameworks (Django, Flask), databases, frontend tech (HTML, JS), remote interpreters, etc.

Initial Setup Tips:
- Configure UI theme: Light/Dark
- Set font size for coding comfort
- Enable "Power Save Mode" when running on low battery

2. Creating a New Project

File → New Project
- Select:
    - Pure Python
    - Django / Flask / FastAPI (Professional only)
    - Set interpreter:
        - venv (Virtual Environment) (recommended)
        - Conda
        - System Python
        - Docker (Pro)

- PyCharm auto-generates:
    - Project folder
    - main.py
    - Virtual environment setup

3. User Interface (UI) Overview

| Section                 | Purpose                                         |
| ----------------------- | ----------------------------------------------- |
| **Project Tool Window** | Shows file/folder structure of your project     |
| **Editor**              | Where you write code                            |
| **Tool Windows**        | Python Console, Terminal, Version Control, etc. |
| **Navigation Bar**      | Breadcrumbs and quick navigation                |
| **Run/Debug Panel**     | Buttons to run/debug code                       |
| **Status Bar**          | Info on Git, interpreter, problems, etc.        |

4. Running Python Code

Ways to Run:
- Right-click .py file → Run
- Click the green triangle
- Use shortcut: Shift + F10
- Create custom configurations via:
- Run → Edit Configurations

5. Python Console vs Terminal

| Tool               | Use Case                                    |
| ------------------ | ------------------------------------------- |
| **Python Console** | Execute Python interactively (like REPL)    |
| **Terminal**       | Run `pip`, `git`, `ls`, etc. (shell access) |

6. Virtual Environment Management

- Auto-created with project
- Manage via:
File → Settings → Project: <project> → Python Interpreter
- Can also use:
    - virtualenv
    - conda (if installed)
    - Docker (Pro)
    - Remote interpreter over SSH (Pro)

7. Navigation & Search

| Feature                   | Shortcut                  | Use                          |
| ------------------------- | ------------------------- | ---------------------------- |
| **Search Everywhere**     | `Shift` twice             | Find files, classes, symbols |
| **Find File**             | `Ctrl + Shift + N`        | Jump to any file by name     |
| **Find Symbol**           | `Ctrl + Alt + Shift + N`  | Jump to class/function names |
| **Go to Definition**      | `Ctrl + B / Ctrl + Click` | Jump to declaration location |
| **Navigate Back/Forward** | `Ctrl + Alt + Left/Right` | Like browser back/forward    |

8. Code Intelligence & Suggestions

- Autocomplete: Ctrl + Space
- Quick Documentation: Ctrl + Q
- Error Checking: Red/yellow underlines
- Intention Actions: Alt + Enter for suggestions

9. Find and Replace

- Find in File: Ctrl + F
- Replace in File: Ctrl + R
- Find in Project: Ctrl + Shift + F
- Replace in Project: Ctrl + Shift + R

10. Unit Testing

- Supports: unittest, pytest, nose
- Create test:
    - Right-click folder → Mark Directory as → Test Sources Root
    - Add test config in Run → Edit Configurations → Python Tests

- UI:
    - Green/Red indicators
    - Filter by passed/failed
    - Stack trace and logs

11. Refactoring Tools

| Action                 | Shortcut         |
| ---------------------- | ---------------- |
| Rename                 | `Shift + F6`     |
| Extract Method         | `Ctrl + Alt + M` |
| Extract Variable       | `Ctrl + Alt + V` |
| Inline Variable        | `Ctrl + Alt + N` |
| Quick Fix / Intentions | `Alt + Enter`    |

12. Code Formatting

- Auto Format: Ctrl + Alt + L
- Organize Imports: Ctrl + Alt + O

- Configure:
    - Settings → Code Style → Python

- Integrate:
    - Black (formatter)
    - isort (import sorter)
    - flake8 / pylint

13. Git & Version Control Integration

- VCS support: Git, GitHub, GitLab, Mercurial, etc.

- Git Panel:
    - Commit (Ctrl + K)
    - Pull (Ctrl + T)
    - Push (Ctrl + Shift + K)
    - Show Diff, History, Annotations

- Manage branches, resolve conflicts visually
