# WeebWeb Dictionary

## Introduction

WeebWeb Dictionary is a simple command-line dictionary program implemented in C++. It allows users to search for word definitions, retrieve a random word, and view recent searches. This project is built using a trie data structure for efficient word storage and retrieval.

## Features

1. **Word Search:** Users can search for the definition of any word present in the dictionary.
   
2. **Random Word Generation:** Users can get a random word along with its definition from the dictionary.
   
3. **Recent Searches:** The program keeps track of the last 10 searched words, allowing users to view their recent searches.

## Implementation Details

1. **Trie Data Structure:** The dictionary is implemented using a trie, a tree-like data structure used for efficient retrieval of a key in a large set of strings.
   
2. **Recent Search Cache:** The program maintains a cache of the last 10 searched words using a queue and a set. This allows quick retrieval of recent searches and ensures that the cache does not exceed 10 words.
   
3. **User Interface:** The program presents a simple command-line interface where users can choose from various options using a menu.

## How to Use

1. **Search for a Word:**
   - Choose option 1 from the menu.
   - Enter the word you want to search for.
   - The program will display the definition of the word if found in the dictionary.

2. **Get Word of the Day:**
   - Select option 2 from the menu.
   - The program will display a random word along with its definition.

3. **View Recent Searches:**
   - Choose option 3 from the menu.
   - The program will display the last 10 searched words.

4. **Exit:**
   - Select option 4 from the menu to exit the program.

## Dependencies

- C++ Standard Library

## Building and Running

1. Ensure you have a C++ compiler installed on your system.
2. Compile the source code (main.cpp) using the compiler.
3. g++ Dictionary.cpp -o Dictionary
4. Run the compiled executable.

## Contributors

- Abhigyan Pratap Singh
