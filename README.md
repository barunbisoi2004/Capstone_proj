# Terminal File Explorer (C++ + Ncurses)

This project is a **terminal-based file explorer** built in **C++** using the **C++17 `<filesystem>` library** and the **Ncurses** library for user interface rendering.  
It allows users to navigate directories, manage files, modify permissions, search files, and perform clipboard operations (copy, cut, paste) directly from a terminal environment.  
This system is especially useful on **Linux servers, SSH terminals, and low-resource systems** that do not support GUI-based file managers.

---

## 🚀 Features

| Feature | Description |
|--------|-------------|
| **Directory Navigation** | Move through folders and return to parent directories |
| **Create Files & Directories** | Quickly generate new files or folders |
| **Rename & Delete** | Manage items efficiently |
| **Copy / Cut / Paste** | Works for both files and folders |
| **Change Permissions** | Set Unix numeric permissions (e.g., 755, 644) |
| **Search** | Find files by name recursively |
| **Ncurses UI** | Styled interactive terminal interface |
| **Keyboard Shortcuts** | Smooth, fast, keyboard-only workflow |

---

## 🎮 Keyboard Controls

| Key | Action |
|----|--------|
| ↑ / ↓ | Move cursor |
| **Enter** | Open directory |
| **←** | Go to parent directory |
| **n** | Create new file |
| **m** | Create new folder |
| **r** | Rename item |
| **d** | Delete item |
| **c** | Copy item |
| **x** | Cut item |
| **v** | Paste item |
| **p** | Change permissions |
| **/** | Search files/folders |
| **q** | Quit the application |

---

## 🛠️ Installation & Build Instructions

### **Windows (MSYS2 - Recommended)**

Install dependencies:
```bash
pacman -S mingw-w64-x86_64-gcc mingw-w64-x86_64-ncurses
