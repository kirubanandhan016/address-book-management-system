# 📒 Address Book Management System

<p align="center">
  <img src="https://img.shields.io/badge/Language-C-A8B9CC?style=for-the-badge&logo=c&logoColor=white" alt="C Language"/>
  <img src="https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows"/>
  <img src="https://img.shields.io/badge/Storage-File%20Handling-8B5CF6?style=for-the-badge" alt="File Handling"/>
  <img src="https://img.shields.io/badge/Status-Active-22C55E?style=for-the-badge" alt="Project Status"/>
</p>

<p align="center">
  <b>A simple, efficient, and menu-driven contact management application built using C.</b>
  <br/>
  Store, organize, and manage your contacts with file handling and input validation.
</p>

---

## ✨ About the Project

The **Address Book Management System** is a console-based application developed in C to simplify contact management. It demonstrates core C programming concepts, modular code organization, file operations, and input validation.

The project is designed to provide a practical understanding of how a real-world application can manage contact information and preserve data between program executions.

## 🚀 Features

- 📇 **Contact Management** — Organize and manage contact information.
- 💾 **File Handling** — Store contact data in files for persistence.
- ✅ **Input Validation** — Validate user input to help prevent invalid entries.
- 🧩 **Modular Architecture** — Separate source files for contacts, file operations, and validation.
- 🖥️ **Console Interface** — Simple, menu-driven interaction.
- 🔍 **Maintainable Code** — Use header files to organize declarations and functionality.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| C | Core application development |
| GCC | Compilation |
| File Handling | Persistent data storage |
| Header Files | Modular code organization |
| PowerShell | Build and execution on Windows |

## 📂 Project Structure

```text
AddressBook-NewDesign/
│
├── main.c              # Main program and menu
├── contact.c           # Contact management operations
├── contact.h           # Contact declarations
├── file.c              # File operations
├── file.h              # File handling declarations
├── validation.c        # Input validation
├── validation.h        # Validation declarations
├── contacts.txt        # Contact data storage
├── documentation.txt   # Project documentation
└── README.md           # Project overview
```

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/address-book-management-system.git
```

### 2. Navigate to the project folder

```bash
cd address-book-management-system
```

### 3. Compile the source files

Make sure GCC is installed and available in your terminal.

```bash
gcc main.c contact.c file.c validation.c -o addressbook.exe
```

### 4. Run the application

**Windows PowerShell:**

```powershell
.\addressbook.exe
```

**Linux:**

```bash
gcc main.c contact.c file.c validation.c -o addressbook
./addressbook
```

> **Note:** Run the application from the project directory so that relative file paths for contact storage work as expected.

## 🧠 Concepts Practiced

- Structures and functions in C
- Header files and modular programming
- File input/output operations
- Input validation and error handling
- Compilation and debugging
- Command-line application development
- Git and GitHub project management

## 🎯 Project Goals

- Strengthen practical C programming skills.
- Understand how data can be stored using file handling.
- Build a modular and maintainable console application.
- Apply programming fundamentals to a practical project.

## 🔮 Future Improvements

- ✏️ Edit existing contacts
- 🔎 Search contacts by name or phone number
- 🗑️ Delete contacts safely
- 📋 Sort and display contacts efficiently
- 🔐 Add stronger input validation
- 🗄️ Integrate a database such as SQLite

*These are potential enhancements; availability depends on the implemented functionality.*

## 👨‍💻 Author

**Kirubanandhan V**

Aspiring Python Backend Developer | C | C++ | Python | SQL | FastAPI

- 💼 LinkedIn: [Connect with me](https://www.linkedin.com/in/kirubanandhan-v-98bb83443/)
- 🐙 GitHub: [Explore my repositories](https://github.com/YOUR-USERNAME)

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

---

<p align="center">
  <b>Built with C, curiosity, and a commitment to learning. 🚀</b>
</p>
