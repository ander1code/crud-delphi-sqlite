# CRUD-Delphi-SQLite
![Programming Language: Delphi](https://img.shields.io/badge/Delphi-orange?logo=delphi)
![SQLite](https://img.shields.io/badge/SQLite-blue?logo=sqlite)
![Platform: Windows](https://img.shields.io/badge/Windows-blue?logo=windows) 
![Last Commit](https://img.shields.io/github/last-commit/example/crud-delphi-sqlite?color=yellow&logo=github) ![Size](https://img.shields.io/github/repo-size/example/crud-delphi-sqlite?color=blue&logo=files) ![License](https://img.shields.io/github/license/example/crud-delphi-sqlite?color=black&logo=open-source-initiative)

## 1. Description
A **registration system** developed in **Delphi 7**, utilizing an **SQLite database** for efficient data handling. This project includes various functionalities such as user management, reporting, and data security features.

## 2. System Characteristics
- **Database Connection Configuration:** SQLite
- **Authentication:** Login system secured with **MD5 hashing**.
- **Registrations:** Allows the registration of physical persons.
- **Search Functionality:** Enables searches for registered physical persons.
- **Reports Generation:** Provides reporting capabilities.
- **User Management:** Includes tools for managing application users.
- **Toolbar Icon Management:** Features the ability to hide icons in the toolbar.

## 3. Software and Tools Used
### Development Environment
- **IDE:** Borland Delphi 7 - Enterprise

### Libraries and Dependencies
- **Database Connection:**
  - **ZeosLib:** [ZeosLib on SourceForge](https://sourceforge.net/projects/zeoslib/)
  - **SQLite:** [SQLite Official Site](https://www.sqlite.org/index.html)
- **Regular Expression Handling:**
  - **PCRE Wrapper for Delphi 7:** [PCRE Wrapper](http://renatomancuso.com/software/dpcre/dpcre.htm)
- **Hashing:**
  - **MD5:** Provides secure login handling.  
    Description: "This file is part of the CACIC program - Automatic Configurator and Collector of Computational Information."  
    [Forum Link](http://forum.datasus.gov.br/viewtopic.php?t=7376)
- **Tray Icon Management:**
  - **Tray Icon Component:** [Tray Icon Component on SourceForge](https://sourceforge.net/projects/rxlib/files/)

### Design Patterns Used
The following design patterns were implemented in the project to ensure maintainability and scalability:
- **Singleton**
- **Facade**
- **Factory**
- **Abstract Factory**
- **Adapter**