## Getting Started

Welcome to the VS Code Java world. Here is a guideline to help you get started to write Java code in Visual Studio Code.

## Folder Structure

The workspace contains two folders by default, where:


- `src`: the folder to maintain source files
- `lib`: the folder to maintain dependencies
- `bin`: the folder where compiled output files will be generated


##  Building and Running Your Java Project
1. Compiling Java Files
To compile your Java files, navigate to your project directory in the terminal and run:

`javac -d bin src/*.java` or `javac -encoding UTF-8 -d bin src/*.java`

- `javac` is the Java compiler.
- `-d bin` specifies that compiled .class files should be placed in the bin directory.
- `src/*.java` compiles all Java source files in the src directory.

2. Running the Compiled Java Program
After compiling, run your Java application with:

`java -cp bin App`

- `-cp bin` tells Java to look for compiled files in the bin directory.

`App` is the name of your main class (without .class extension).

If your Java files contain a package declaration (e.g., package mypackage;), you need to run: