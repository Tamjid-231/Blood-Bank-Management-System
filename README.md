# Blood Bank Management System

> **Project type:** Academic Project

This is an academic, menu-based console project written in C. I created it to practise structures, arrays, functions, searching and updating records.

## Features

- Add a blood group and its available quantity
- Search for a blood group by blood type
- Display all stored blood groups
- Update the quantity of an existing blood group
- Delete a blood group
- Display a simple blood group package

## How it works

Each record contains a blood type and quantity. The records are stored in a fixed-size array of C structures while the program is running. The current limit is 100 records.

The project does not use a database or file storage, so the entered data is removed when the program closes.

## Run the project

A C compiler such as GCC is required.

```bash
gcc blood_bank_management_system.c -o blood_bank
```

Run on Windows:

```bash
blood_bank.exe
```

Run on Linux or macOS:

```bash
./blood_bank
```

## Repository contents

- C source code
- Project explanation in PDF format
- Archived project copy

## Important note

This is an academic programming project. It is not designed for real medical or blood-bank operations.

## Author

Md. Tamjid Hossain
