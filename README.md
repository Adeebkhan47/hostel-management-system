# Hostel Management System

A comprehensive console-based Hostel Management System developed in C programming language for managing student records in hostel accommodations.

## 📋 Overview

This project is a terminal-based application designed to manage student information in a hostel environment. It provides a complete solution for hostel administrators to maintain student records, room assignments, and payment tracking across multiple hostel buildings.

## 🏢 Supported Hostels

The system manages four hostel buildings:
- **BH-1** (Boys Hostel 1)
- **BH-2** (Boys Hostel 2) 
- **BH-3** (Boys Hostel 3)
- **GH-1** (Girls Hostel 1)

Each hostel accommodates up to 10 rooms.

## ✨ Features

### Core Functionality
- **Student Registration**: Add new student entries with complete information
- **Record Updates**: Modify existing student information
- **Student Search**: Look up specific student details
- **View All Records**: Display complete list of all registered students
- **Student Removal**: Delete student records from the system
- **Password Protection**: Secure access to the management system

### Student Information Management
The system stores comprehensive student data including:
- Personal Information (Name, Age, Date of Birth, City)
- Contact Details (Phone Number, Email ID)
- Family Information (Father's Name, Father's Phone Number)
- Hostel Details (Room Number, Hostel Name, Hostel ID)
- Financial Information (Rent Payment Status)

## 🚀 Getting Started

### Prerequisites
- GCC Compiler (or any C compiler)
- Windows/Linux/macOS terminal
- Basic understanding of C programming

### Installation & Compilation

1. **Clone or Download the Repository**
   ```bash
   git clone <repository-url>
   cd hostel-management-system
   ```

2. **Compile the Program**
   ```bash
   gcc 1.c -o hostel_management
   ```

3. **Run the Application**
   ```bash
   ./hostel_management
   ```
   Or on Windows:
   ```cmd
   hostel_management.exe
   ```

## 🎮 Usage

### Main Menu Options

1. **Enter new Student [1]**
   - Add a new student to the hostel database
   - Input all required personal and hostel information

2. **Update student information [2]**
   - Modify existing student records
   - Search by student ID and update details

3. **Check student details [3]**
   - Search and view specific student information
   - Lookup by student ID

4. **View all students list [4]**
   - Display complete list of all registered students
   - Shows all students across all hostels

5. **Remove existing Student [5]**
   - Delete student records from the system
   - Permanently removes student data

6. **Exit [6]**
   - Safely exit the application

### Authentication
The system includes password protection. You'll need to enter the correct password to access the main menu.

## 📁 File Structure

```
project/
├── 1.c                          # Main source code file
├── 1.exe                        # Compiled executable
├── README.md                    # Project documentation
├── record.txt                   # Main student records database
├── BH-1.txt                     # Boys Hostel 1 student IDs
├── BH-2.txt                     # Boys Hostel 2 student IDs
├── BH-3.txt                     # Boys Hostel 3 student IDs
├── GH-1.txt                     # Girls Hostel 1 student IDs
├── pseudosode.txt               # Pseudocode documentation
├── Flowchart(Project).drawio    # Project flowchart
├── codetoflow.png               # Code flow diagram
├── GROUP 12.pptx                # Project presentation
└── Pseudo Code(Project).docx    # Detailed pseudocode document
```

## 💾 Data Storage

- **record.txt**: Main database file storing all student information
- **BH-1.txt, BH-2.txt, BH-3.txt, GH-1.txt**: Individual hostel files containing student IDs for each building
- Data is stored in plain text format for easy portability

## 🔧 Technical Details

### Programming Language
- **C Programming Language**
- Standard C libraries used: `stdio.h`, `stdlib.h`, `string.h`, `math.h`, `time.h`, `conio.h`

### Key Features Implementation
- **Struct-based Data Management**: Uses structures to organize student information
- **File I/O Operations**: Persistent data storage using file handling
- **Menu-driven Interface**: Interactive console-based user interface
- **Date/Time Integration**: Real-time date display in the system
- **Input Validation**: Basic input validation and error handling

## 🎯 Project Context

This project was developed as part of:
- **Course**: Programming Fundamentals (PF)
- **Semester**: 1st Semester, BS Software Engineering
- **Academic Project**: Lab Assignment/Project

## 👥 Development Team

**Group 12** - BS(SE) Students

## 📊 Project Documentation

The project includes comprehensive documentation:
- **Flowchart**: Visual representation of program flow
- **Pseudocode**: Detailed algorithm documentation
- **Presentation**: Project overview and demonstration

## 🔒 Security Features

- Password-protected access to prevent unauthorized usage
- Secure file handling for data integrity

## 💰 Rent Management

- Standard rent amount: ₹5000 per student
- Payment tracking and status monitoring
- Financial record maintenance

## ⚠️ Important Notes

1. **Data Backup**: Always backup your data files before making changes
2. **File Permissions**: Ensure proper file permissions for read/write operations
3. **Input Format**: Follow the specified input formats for dates (mm/dd/yyyy)
4. **Room Capacity**: Each hostel is limited to 10 rooms

## 🐛 Known Issues

- Some file opening modes in the code may need adjustment for different compilers
- Input validation could be enhanced for better error handling

## 🚀 Future Enhancements

Potential improvements for the system:
- GUI implementation using graphics libraries
- Database integration (MySQL/SQLite)
- Advanced search and filtering options
- Report generation features
- Backup and restore functionality
- Multi-user access with different permission levels

## 📝 License

This project is developed for educational purposes as part of academic coursework.

## 🤝 Contributing

This is an academic project. For educational purposes, feel free to:
- Study the code structure
- Suggest improvements
- Report issues
- Create enhanced versions

---

**Note**: This project demonstrates fundamental programming concepts including file handling, structures, functions, and menu-driven programming in C language.