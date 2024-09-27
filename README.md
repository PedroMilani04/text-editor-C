# Simple Text Editor - University Project

This project is a simple, lightweight text editor developed in **C** for a university course. The editor is inspired by the **Kilo Text Editor**, a minimalist text editor written by Salvatore Sanfilippo. The goal of this project was to create a functional text editor in a Linux environment with basic text editing features and a focus on simplicity and small code size.

## Features
- **Cross-platform**: Runs on any Unix-based system (developed and tested on Linux).
- **Basic Text Editing**: Open, edit, and save plain text files.
- **Syntax Highlighting**: Supports syntax highlighting for some common programming languages (similar to Kilo).
- **Navigation**: Move the cursor using arrow keys, jump between lines, and edit text efficiently.
- **Responsive Interface**: Instant feedback while typing, with a simple and intuitive command interface.
- **No External Libraries**: Written in pure C, using only standard libraries and terminal I/O for portability.

## How to Use
1. **Compile**: Since the project is written in C, you need to compile the source code.
   ```bash
   make kilo (File name)
   ```
   in your respective Linux folder

## Inspiration
- https://github.com/antirez/kilo <br>
The Kilo Text Editor is a 1000-line text editor created by Salvatore Sanfilippo (also known for creating Redis) as a demonstration of how to build a simple text editor from scratch using minimal code. Like Kilo, this editor is designed to be lightweight and easy to understand, making it a great learning tool for understanding terminal I/O, text buffers, and handling user input.
