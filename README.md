# Address Book Management System (C)

A menu-driven C application for storing and managing contact records using file handling and input validation.

## Features

- Contact management through a console interface
- File-based contact storage
- Input validation
- Modular C source and header files

## Technology

C · GCC · File I/O · Header files

## Build and run

Clone the repository:

```bash
git clone https://github.com/kirubanandhan016/address-book-management-system.git
cd address-book-management-system
```

Compile with GCC:

```bash
gcc main.c contact.c file.c validation.c -o addressbook
```

On Windows, you can compile to an executable named `addressbook.exe`:

```powershell
gcc main.c contact.c file.c validation.c -o addressbook.exe
.\addressbook.exe
```

On macOS/Linux:

```bash
./addressbook
```

Run the program from the project directory if it uses relative paths for its data files. Confirm source filenames match the compile command if the project structure changes.

## Project scope

This is a C programming project, included as supporting evidence of programming fundamentals. It is not a Python backend service.

## Author

**Kirubanandhan V** · [GitHub](https://github.com/kirubanandhan016)
