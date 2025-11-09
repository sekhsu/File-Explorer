# File-Explorer

A simple file-explorer application written in C++ designed as a capstone project.

## 🚀 Overview

This project offers a basic command-line file explorer allowing users to browse, inspect and manage file system entries (files and folders). It is implemented in C++ and demonstrates foundational concepts in file input/output, directory traversal, user interaction and simple UI logic.

## ✅ Features

- List files and directories in a given path.  
- Navigate into sub-directories and move back to parent directories.  
- Display file properties (e.g., name, size, date modified).  
- Simple text-based menu for user selection and navigation.  
- Built as part of a capstone / academic project, showing design and implementation of a small file-system utility.

## 🛠 Getting Started

### Prerequisites

- A C++ compiler supporting C++11 (or later) standard.  
- A compatible operating system (Linux, Windows, or Mac) where filesystem functions are supported.

### Build

1. Clone the repository:
   ```bash
   git clone https://github.com/sekhsu/File-Explorer.git
   cd File-Explorer
2. Compile the source code (example using g++):

g++ -std=c++11 file\ explorer.cpp -o file-explorer

3. Run the program:

./file-explorer

Usage

Upon running, you will be prompted to enter a starting directory path.

The program lists contents of that directory with indexes.

Choose an index to navigate into a folder or view file details.

Option to go back/up a directory.

Exit when done.

📚 Project Structure
/
├── file explorer.cpp     # Main source file (C++ implementation)
├── CAPSTONE PROJECT REPORT.pdf  # Project documentation and report
├── README.md             # (this file) Project read-me

👨‍💻 Why This Project?

Serves as a hands-on exercise in C++ programming, file system APIs, directory traversal and user interface logic.

Suitable for beginners who wish to understand how file explorers and file-system utilities can be built from scratch.

Provides a base that can be extended (e.g., add file search, file operations like copy/move/delete, GUI interface, etc.).

🔧 Future Enhancements

Add operations: copy, move, delete files and folders.

Integrate a GUI (e.g., using Qt or wxWidgets) for a graphical experience instead of CLI.

Add sorting, filtering, and search capabilities.

Add support for viewing file contents (text files) or previews (images).

Add cross-platform enhancements and error-handling improvements.

📝 License

Insert the license under which this code is released (e.g., MIT, GPLv3).
If no license is specified, please assume “All rights reserved” until clarified.

📞 Contact / Support

For issues, suggestions or contributions, please open an issue on the GitHub repository or contact the author.

Thank you for checking out File-Explorer! Feel free to use, modify or extend it to suit your needs.
---
