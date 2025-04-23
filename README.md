# Systemcall-interface
The Secure System Call Interface is a user-friendly web-based application that provides controlled access to low-level system calls (such as open, read, write, delete, etc.) with built-in security, logging, and validation features. 

🔒 Access Control
Blocks access to critical system directories (/etc, /bin, /usr/bin, etc.) to prevent accidental or malicious modifications.

📋 Logging System
Every action performed via the interface is logged with details for auditing and monitoring purposes.

✅ User-Friendly Interface
Built with React and modern UI libraries (e.g., shadcn/ui), the interface allows users to easily select operations, input file paths, and view results.

📂 Supported Operations
Includes:

File open, read, write, close

File delete, rename

Permission control via chmod

Ownership changes via chown
