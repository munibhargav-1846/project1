Abstract

The Venue Management System is a simple, terminal-based application developed in C for managing venue records efficiently. The system provides fundamental functionalities including adding new venue details, searching for venues by ID or name, updating existing records, and deleting entries when necessary. All venue information is stored persistently in a binary .dat file, ensuring that data remains available across multiple sessions. Designed for ease of use, the program offers a menu-driven interface suitable for beginners and small-scale event management setups. This project demonstrates essential concepts of file handling, data structures, and control flow in C, providing a practical solution for managing venue data in a lightweight and accessible format.

FEATURES OF THE PROGRAM

Add new venue records with details (venue name, location, capacity, contact info, availability, etc.)

View all stored venue records in a clean, organized list

Search for venues by ID or Name

Update existing venue information

Delete venue records from the database

Persistent data storage using a .dat file

Fully terminal-based (CLI) interface

Beginner-friendly and easy-to-understand C program structure

Automatically creates the data file if it doesn’t exist

Basic error handling for invalid input and missing files

TECHNICAL REQUIREMENTS

1. System Requirements

Operating System: Windows / Linux / macOS

Terminal or command-line environment

Minimum RAM: 4 MB

Minimal disk space for the .dat file

2. Software Requirements

C Compiler: GCC / MinGW / Clang / MSVC

Any text editor or IDE (VS Code, Code::Blocks, Dev-C++, Vim, etc.)

Optional: Make tool (if using a Makefile)

3. Programming Requirements

Language: C

Supported C Standards: C89 / C99 / C11

Standard libraries used:

<stdio.h>

<stdlib.h>

<string.h>

4. File Handling Requirements

Read/write access to the working directory

Venue records stored in a binary .dat file

Program automatically creates the data file if missing

5. Compilation Requirements

Code compiles without errors

Recommended flag:

-Wall

FUNCTIONAL REQUIREMENTS

1. User Interface

Fully terminal-based interface

Clearly displays all menu options

Accepts and validates user inputs

2. Venue Record Operations
Add Venue

Enter and save new venue information such as:

Venue name

Location

Capacity

Contact

Availability

Additional details

Search Venue

Search by:

Venue ID

Venue Name

View Venues

Display all stored venue records in a clean layout.

Update Venue

Modify existing venue details.

Delete Venue

Remove a venue record permanently from the database.

3. Data Management

Stores all venue details in a persistent .dat file

Ensures information remains across multiple sessions

Handles missing or new data files automatically

4. Program Flow

Uses a menu-driven loop until the user chooses Exit

Displays appropriate messages for actions

Allows smooth navigation between operations

HOW TO RUN THE PROGRAM

1. Compile the Program

Open your terminal inside the project folder and run:

gcc venue_management.c -o venue_management

2. Run the Executable

Linux/macOS

./venue_management

WINDOWS

venue_management.exe

3. Data File

Program automatically creates:

venues.dat


All venue records are stored and retrieved from this file

SCREENSHORTS (Expected Outputs)

Main Menu

<img width="320" height="141" alt="Screenshot 2025-11-20 163153" src="https://github.com/user-attachments/assets/94a0d793-ab7c-4709-8856-87e78a6f1412" />


Add New Venue

<img width="339" height="169" alt="Screenshot 2025-11-20 163207" src="https://github.com/user-attachments/assets/aaad8987-62f5-4c03-af19-1e7d4d51de45" />


View All Venues

<img width="296" height="153" alt="Screenshot 2025-11-20 163216" src="https://github.com/user-attachments/assets/99086fa6-f716-4776-beab-840ee8e75371" />


Search Venue

<img width="428" height="189" alt="Screenshot 2025-11-20 163224" src="https://github.com/user-attachments/assets/631135c7-071c-4535-a78d-a0d91fe959b0" />


Delete Venue

<img width="441" height="133" alt="Screenshot 2025-11-20 163249" src="https://github.com/user-attachments/assets/8960f4af-90eb-481f-98f4-b0f6599e1d9c" />


Exit Screen

<img width="595" height="60" alt="Screenshot 2025-11-20 163316" src="https://github.com/user-attachments/assets/de91bb82-c3cc-4c7c-b679-bc2865e0a073" />

