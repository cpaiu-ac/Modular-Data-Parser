# Modular-Data-Parser
# C++ Modular File Processing & Data Parsing

## 📌 About the Project
This repository demonstrates professional C++ project structuring and file I/O operations. Instead of a monolithic single-file script, this project is built using a modular architecture, separating declarations, implementations, and the main execution loop. 

This approach is fundamental in automotive software engineering and embedded systems, where code maintainability, reusability, and clean architecture are mandatory for large-scale projects (such as Automotive Platform Build Systems).

## ⚙️ Core Features
* **Modular Architecture:** Clean separation of concerns using header files for declarations and separate source files for logic implementation.
* **File I/O Operations:** Dynamically reads and processes external input data streams rather than relying on hardcoded variables.
* **Code Reusability:** Functions are structured to be easily exported or integrated into larger systems.

## 🛠️ Tech Stack & Concepts
* **Language:** C/C++
* **Concepts:** Modular Programming, File Input/Output (I/O) Streams, Header Inclusion Guards, Data Parsing.

## 📁 Repository Structure
* `main.cpp` (formerly main.txt) - The entry point of the application, managing the execution flow.
* `header.h` (formerly header.txt) - Contains the function prototypes, structural definitions, and necessary library includes.
* `functii.cpp` (formerly functii.txt) - The core implementation file containing the business logic and algorithms.
* `date_intrare.txt` (formerly date intrare.txt) - The external raw data file processed by the program.
