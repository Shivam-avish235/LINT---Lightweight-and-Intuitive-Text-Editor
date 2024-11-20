# LINT 
LINT is a terminal-based text editor inspired by nano. Written in C with under 1068 lines of code, it features syntax highlighting and search functionality, making it a lightweight yet powerful tool for terminal users. Built using the guide from KILO - Build Your Own Text Editor by Antirez, with full credit for inspiration.

Link of the article - https://viewsourcecode.org/snaptoken/kilo/

### Table Of Contents
- [Installation](#installation)
- [USAGE](#usase)
- [IMAGES/VIDEOS](#IMAGES)
- [CREDITS](#credits)

## IMAGES
### SYNTAX HIGHLIGHTING
![MAIN EDITOR](https://github.com/Shivam-avish235/LINT---Lightweight-and-Intuitive-Text-Editor/blob/main/highlight_text.png)
### NORMAL
![SYNTAX](https://github.com/Shivam-avish235/LINT---Lightweight-and-Intuitive-Text-Editor/blob/main/normal.png)

## Installation

### Prerequisites
- Ensure you have GCC (GNU c compiler)
- Make sure you have make installed(optional)
- Ensure you have git installed

### METHOD 1 - using GCC
#### STEPS TO INSTALL

1. Clone the repository OR just download Lint.c:
    ```bash
        git clone https://github.com/Shivam-avish235/Lint
2. Navigate to Directory
    ```bash
        cd Lint
3. Compile Using GCC
    ```bash
        gcc Lint.c -o Lint
4. Run
    ```bash
        ./Lint

### METHOD 2 - using MAKE
#### STEPS TO INSTALL
1. Clone the repository OR just download Lint.c:
    ```bash
        git clone https://github.com/Shivam-avish235/LINT---Lightweight-and-Intuitive-Text-Editor
2. Navigate to Directory
    ```bash
        cd LINT---Lightweight-and-Intuitive-Text-Editor
3. Install Make(skip it if you have already)
    ```bash
        sudo apt install make
4. Compile using make
    ```bash
        make
5. RUN
    ```bash
        ./Lint
    

## USASE
- Search
    1. CTRL+F to search
    2. Use Arrow keys to go to next result or previous
    3. Use ESC to exit search

- Saving a File
    CTRL+S to save

- Quiting LINT
    1. CTRL+Q to quit
    2. Press CTRL+Q 3 times if your file is not saved!
       
## CREDITS

- [SHIVAM](https://github.com/Shivam-avish235)
- [ANTIREZ'S KILO](https://viewsourcecode.org/snaptoken/kilo/) 
