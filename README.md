# Search Engine

This project is a simple file-based search engine implemented in C++. It allows you to search for text within files located in a specified folder and outputs the results to a text file. You can perform searches either manually or by reading from a query file.

## Features

- **Manual Search**: Enter queries directly in the console.
- **File-based Search**: Reads queries from a specified file (`query.txt`).
- **Results Output**: Outputs the results of each query into `answer.txt`.

## Prerequisites

- **C++ Compiler**: Ensure you have a C++ compiler installed (e.g., `g++` for Windows, Linux, or macOS).
- **Basic Command Line Knowledge**: You will need to compile and run the code from the command line.

## Setup Instructions

1. **Clone or Download the Repository**: Place all project files in a single folder.
   
2. **Modify the Database Folder**: 
   - Place the files you want the search engine to search through inside this `Database` folder. Each file should contain text content you want to search within.

## Compilation 

1. Open a terminal (or command prompt) and navigate to the project folder.
2. Compile the C++ files using the following command:

   ```bash
   g++ CS163.cpp helperMethod.cpp trie.cpp -o search_engine.exe
   ```
3. This will create an executable file named `search_engine.exe`.

## Usage

1. Run the executable by entering:
   ```bash
   search_engine.exe
   ```
2. You will be prompted with options:

- Manual Search: Type queries directly in the console.
- File-based Search: The program will read queries from `query.txt` and search for each query in the files within the `Database` folder.

3. After the search is complete, check `answer.txt` for the search results. The file will include each query followed by the filenames and content matches, or a "Not found" message if there are no results.

## Output
- `answer.txt`: This file contains the results of each search query, generated automatically after the program runs.
