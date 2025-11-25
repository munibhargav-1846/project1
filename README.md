🏢 VENUE MANAGEMENT SYSTEM (C Programming)
📄 ABSTRACT
The Venue Management System is a terminal-based application written in C that enables users to manage event venue bookings efficiently. It provides essential capabilities such as adding, viewing, searching, updating, and deleting event booking details.

All records are stored persistently in a binary file (venue.txt) ensuring the data remains saved across program runs.

This project illustrates key C programming concepts such as structures, file handling, control flow, loops, and modular design. It is suitable for beginners, coursework, and practical learning.​

✨ FEATURES
Core Functionalities
➕ Add new event booking records (Venue ID, Event Name, Date, Organizer, Contact No)
📋 Display all bookings in a formatted table
🔍 Search booking by Venue ID
✏️ Update event booking information
❌ Delete venue booking records
💾 Persistent data storage using binary file (venue.txt)
🖥️ Fully terminal-based, menu-driven interface
👨‍💻 Beginner-friendly modular code
⚙️ Auto-creates the data file if missing
⚠️ Includes basic input validation & error handling

🛠️ TECHNICAL REQUIREMENTS
System Requirements
Operating System: Windows / Linux / macOS
Terminal or Command Prompt
At least 4 MB RAM
Minimal disk space for venue.txt

Software Requirements
C Compiler: GCC / MinGW / Clang / MSVC
Code Editor or IDE: VS Code, Code::Blocks, Dev-C++, etc.
Optional: Make utility (if using a Makefile)

Programming Requirements
Language: C
Standard Supported: C89 / C99 / C11
Header files required:
stdio.h
stdlib.h
string.h

File Handling
Read/Write permissions in working directory
Records stored in binary format (venue.txt)
File auto-created if not found

📌 FUNCTIONAL REQUIREMENTS
User Interface
Terminal-based CLI
Clean menu-driven navigation
Validates user input

🏢 Venue Booking Operations
➕ Add Booking
Enter Venue ID, Event Name, Date, Organizer, Contact No
Saved in venue.txt
📋 Display Bookings
Shows all venue booking records in a clean table format
🔍 Search Booking
Search using unique Venue ID
✏️ Update Booking
Modify Event Name, Date, Organizer, Contact No, etc.
❌ Delete Booking
Permanently removes a booking record using a temporary file method

🔧 DATA MANAGEMENT
Binary file storage → Fast and efficient
Safe updates and deletions
Handles empty/missing file gracefully

🔄 PROGRAM FLOW
Menu runs in a loop
Exit option included
Shows clear success/error messages appropriately

▶️ Running the Program
1️⃣ Compile
gcc venue.c -o venue
2️⃣ Run
Linux / macOS
./venue
Windows
venue.exe
3️⃣ Data File
*Automatically creates venue.txt *Stores all booking data in binary form

📸 Screenshots (Optional)
*Add Booking
*Display Bookings
*Search Booking
*Delete Booking
*Exit

##📝 Author
P.Sasidha
