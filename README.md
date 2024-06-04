# Telephone Directory System

## Overview

The Telephone Directory System is a C++ console application that allows users to manage a simple telephone directory. The application provides functionalities to add, display, search, modify, and delete records. It also features a graphical welcome screen and password protection for accessing the directory.

## Features

- **Add Records**: Input name, address, and phone number to add a new record.
- **Show Records**: Display all records in the directory.
- **Search Records**: Search for a specific record by name.
- **Modify Records**: Update details of an existing record using the phone number as a reference.
- **Delete Records**: Remove a record from the directory by name.
- **Password Protection**: Secure access to the directory with a password.
- **Graphical Interface**: Welcome screen and menu options displayed using graphics.

## Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/10shivanibm/Telephone-Directory-System.git
    ```
2. **Navigate to the project directory:**
    ```sh
    cd Telephone-Directory-System
    ```
3. **Compile the code:**
    ```sh
    g++ -o telephone_directory_system telephone_directory_system.cpp -lgraph
    ```
4. **Run the executable:**
    ```sh
    ./telephone_directory_system
    ```

## Usage

1. **Start the program:**
   Run the executable file. A graphical welcome screen will appear.

2. **Enter the password:**
   The default username is `user` and the password is `1234`. Enter it to access the main menu.

3. **Choose an option:**
   Use the menu to add, show, search, modify, or delete records. The main menu options are:
   - `1`: Add a record
   - `2`: Show all records
   - `3`: Search for a record
   - `4`: Modify a record
   - `5`: Delete a record
   - `6`: Exit the application

## Code Structure

- **Class `stud`:** Handles the data structure for storing records.
  - `char name[20]`: Stores the name.
  - `char address[20]`: Stores the address.
  - `unsigned int ph_no`: Stores the phone number.
  - `void get()`: Takes input for a new record.
  - `void show()`: Displays a record.
  - `void modify()`: Modifies an existing record.

- **Main Function:**
  - Initializes graphics.
  - Password verification.
  - Menu-driven interface for CRUD operations on the telephone directory.

## Requirements

- **Compiler:** GCC with graphics library support (e.g., `libgraph`).
- **OS:** The program was originally designed for Turbo C++ on DOS, so it may need adaptations for modern systems.
