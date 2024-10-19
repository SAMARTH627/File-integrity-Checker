# File-integrity-Checker
This Python-based File Integrity Checker calculates and verifies the SHA-256 hash of all files in a given directory. It's a simple tool for ensuring that files in a directory have not been tampered with or corrupted.

Features:
SHA-256 Hash Calculation: Computes the SHA-256 hash for each file in the specified directory, ensuring a robust and secure file integrity check.

Recursive Directory Traversal: Automatically walks through all files in the provided directory, including subdirectories.

Cross-Platform Compatibility: Works on Linux, Windows, or any system with Python installed.

Usage:
1.Clone the repository or download the script.

2.Run the script and enter the directory path you wish to verify.

3.The tool will print the file names and their corresponding SHA-256 hashes.

Example:
![image](https://github.com/user-attachments/assets/a05b64d0-8889-45d7-857c-bb72a2caaf57)

![image](https://github.com/user-attachments/assets/0226dfb8-e895-4972-8bcd-7ac72b7f7f32)

The hash codes of both files are the same this means that this file in not altered or any malicious code is not added to it. 
Requirements:

1.Python 3.x

2.No external dependencies (uses built-in libraries: os and hashlib)

3.This tool is ideal for quickly verifying the integrity of files in a directory and can be customized to use other hashing algorithms if needed.

