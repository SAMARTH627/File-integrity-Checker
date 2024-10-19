# File-integrity-Checker
This Python-based File Integrity Checker calculates and verifies the SHA-256 hash of all files in a given directory. It's a simple tool for ensuring that files in a directory have not been tampered with or corrupted.

Features:
SHA-256 Hash Calculation: Computes the SHA-256 hash for each file in the specified directory, ensuring a robust and secure file integrity check.
Recursive Directory Traversal: Automatically walks through all files in the provided directory, including subdirectories.
Cross-Platform Compatibility: Works on Linux, Windows, or any system with Python installed.
Usage:
Clone the repository or download the script.
Run the script and enter the directory path you wish to verify.
The tool will print the file names and their corresponding SHA-256 hashes.
Example:


Requirements:
Python 3.x
No external dependencies (uses built-in libraries: os and hashlib)
This tool is ideal for quickly verifying the integrity of files in a directory and can be customized to use other hashing algorithms if needed.

