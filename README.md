# Competitive Programming Setup

Welcome to the Competitive Programming Setup repository! This guide will help you set up your environment for competitive programming using Visual Studio Code (VS Code) and Geany. These editors are powerful tools that can enhance your coding efficiency and streamline your problem-solving process.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Setting up VS Code](#setting-up-vs-code)
- [Setting up Geany](#setting-up-geany)
- [Usage](#usage)
- [Contents](#contents)
- [Contributing](#contributing)
- [License](https://github.com/nxtsourav7/Compitative-Programming-Setup/blob/main/LICENSE)
- [Contact](#contact)

## Introduction

Competitive programming is a challenging and rewarding activity that involves solving algorithmic problems within a set timeframe. To maximize efficiency, having a well-configured development environment is crucial. This repository provides a comprehensive setup for VS Code and Geany, two popular code editors among competitive programmers. Follow the instructions below to configure your setup and get started with competitive programming.

## Prerequisites

To set up your environment for competitive programming, ensure you have the following prerequisites installed as per your operating system:
### Windows
- **GCC/G++**: Install via [MinGW](http://www.mingw.org/).
- **Python**: Download and install from the [official website](https://www.python.org/downloads/).
- **Java (optional)**: Install the JDK from the [Oracle website](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).
- **Node.js (optional)**: Download and install from the [Node.js website](https://nodejs.org/).

### Linux
- **GCC/G++**:  Install via package manager:
  ```bash
  sudo apt install build-essential
  ```

## Setting up VS Code

1. **Install Visual Studio Code**: Download and install VS Code from the [official website](https://code.visualstudio.com/).
2. **Install Extensions**: Enhance your coding experience with the following extensions:
   - **C/C++**: Provides IntelliSense, debugging, and code browsing.
   - **Competitive Programming Helper (cph)**: Quickly compile, run and judge competitive programming problems in VS Code. Automatically download testcases , or write & test your own problems. Once you are done, easily submit your solutions directly with the click of a button!
        - **CPH Config**
            1. Install cph in VS Code and open any folder.
            2. [Install competitive companion](https://github.com/jmerle/competitive-companion#readme) in your browser.
            3. Use Companion by pressing the green plus (+) circle from the browser toolbar when visiting any problem page.
            4. The file opens in VS Code with testcases preloaded. Press Ctrl+Alt+B to run them.
            5. Install the [cph-submit](https://github.com/agrawal-d/cph-submit) browser extension to enable submitting directly on CodeForces.
            6. (optional) Add this two lines in your vs code **setting.json** file (if you use c++).
                ```
                "cph.language.cpp.SubmissionCompiler": "GNU G++20 13.2 (64 bit, winlibs)",
                "cph.general.defaultLanguage": "cpp",
                ```
   - **Code Runner**: Allows you to run code and execute custom command easily.
3. **Set Up User Snippets**: A user snippet typically refers to a piece of code or text that users can insert into a larger codebase or document to accomplish a specific task or function. These snippets are often used to save time, ensure consistency, and reduce errors by reusing commonly used code or text. They can be manually created by users or provided by integrated development environments (IDEs) and text editors to facilitate coding and writing.
    - **Set Up**
        1. Write your desired code. 
        2. Copy and Paste it into [Snippet-Generator](https://snippet-generator.app/) website.
        3. Copy your generated snippet and back to VS Code.
        4. Click lower-left corner gear icon.
        5. Then Spnippets -> cpp (or your used language).
        6. Paste your user generated snippet.


    
    If you faced any problem then watch this [YouTube Video](https://www.youtube.com/watch?v=uqBgvO5DAUc)
       **N.B: This is my [User Snippet](https://github.com/nxtsourav7/Compitative-Programming-Setup/blob/main/VS-Code/User-Snippets/cpp.json)(C++). Just Copy Paste. Type *ff* to trigger code templete.**
5. **Keybindings** (Optional): A keybinding (or key binding) is a specific key or combination of keys on a keyboard that is mapped to perform a particular action within software. Keybindings are used to create shortcuts that can enhance productivity and efficiency by allowing users to quickly execute commands without navigating through menus or using a mouse. These shortcuts can often be customized to suit individual preferences or workflow needs.
    
## Setting up Geany (Optional)

1. **Install Geany**: Download and install Geany from the [official website](https://www.geany.org/).
2. **Configure Build Commands**:
   - **C/C++**: Set up custom build commands for compiling and running C/C++ programs.
   - **Python**: Configure the build menu to execute Python scripts.
3. **Customize Preferences**: Adjust editor preferences for optimal coding efficiency, such as enabling line numbers, syntax highlighting, and auto-completion.
4. **Set Up Templates**: Create code templates for quick access during competitions.

## Contact

For any questions or feedback, please contact.

<a href="mailto:nxtsourav7@gmail.com" target="blank"><img align="center" src="src/images/gmail.svg" alt="nxtsourav7" height="30" width="35" /></a>
<a href="https://fb.com/nxtsourav7" target="blank"><img align="center" src="src/images/facebook.svg" alt="nxtsourav7" height="30" width="40" /></a>
<a href="https://codeforces.com/profile/nxtsourav7" target="blank"><img align="center" src="src/images/codeforces.svg" alt="nxtsourav7" height="35" width="40" /></a>
