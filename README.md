# FILE-HANDLING-PROGRAM
*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SRIBALAJI

*INTERN ID*: CT04DY1002

*DOMAIN*: C PROGRAMMING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH

This C program demonstrates the use of basic file handling operations, specifically writing, appending, and reading text from a file. The program guides the user through entering two separate lines of input, which are then written and appended to a file named test.txt. After storing the input, the program reads and displays the full content of the file on the console. The main objective is to introduce and implement standard file handling functions such as fopen, fgets, fputs, fclose, and to use file modes like "w", "a", and "r" effectively.
The program begins by opening the file test.txt in write mode ("w"). This mode either creates the file if it doesn't exist or clears the existing contents if the file is already present. The user is prompted to enter the first line, which is stored in a character array using the fgets() function. This line is then written to the file using fputs(), and the file is closed using fclose().
In the second stage, the same file is reopened in append mode ("a"), which ensures that new content is added to the end of the file without deleting its existing contents. The user is asked to enter a second line, which is read in the same way and appended to the file. Again, the file is closed after writing.
Finally, the file is opened in read mode ("r"), and its contents are read and displayed using a loop that utilizes fgets() to read line-by-line. The use of a while loop ensures that the entire file is read until the end. This effectively demonstrates how the program stores and retrieves data from a file, mimicking real-world scenarios like saving user data or logs.
The program was developed and executed using Visual Studio Code (VS Code), a popular code editor created by Microsoft. VS Code is a powerful and lightweight source code editor that supports a wide variety of programming languages, including C and C++. It is available on Windows, Linux, and macOS, making it highly accessible to programmers across platforms.
One of the key features of VS Code is its extension system. For C programming, the C/C++ extension by Microsoft enables features like syntax highlighting, code navigation, IntelliSense (auto-completion), and debugging tools. With the help of the integrated terminal, users can easily compile C code using GCC (GNU Compiler Collection) or any other compiler configured in their system. VS Code also supports version control through Git, allowing developers to track changes in their code efficiently.
VS Code is particularly suitable for beginners and intermediate programmers due to its user-friendly interface and robust feature set. It is widely used in academic institutions for teaching programming and software development. The integrated debugger, terminal, and extension support make it an ideal tool for writing, testing, and debugging programs like this file handling example.
In this case, VS Code was used to write the source code, run the program via the terminal, and observe the program’s input and output behavior. It facilitated quick development and testing, making the programming workflow smooth and efficient.This program is especially useful in educational contexts where students are learning about file input/output in C. Understanding how to use different file modes and perform error checking helps build a strong foundation in systems programming. The example covers scenarios commonly encountered in real applications, such as saving user-generated content or processing configuration files.
Furthermore, the inclusion of file error handling (if (fp == NULL)) demonstrates the importance of validating file operations before proceeding. This not only prevents program crashes but also encourages writing robust and reliable software.
In conclusion, this program effectively introduces and implements basic file handling operations in C. By using Visual Studio Code, the development experience is enhanced through features such as live error detection, intelligent code suggestions, and an integrated terminal for compilation and execution. The combination of a practical program and a modern development environment offers a solid learning experience for any beginner in C programming.

#OUTPUT:

<img width="1074" height="645" alt="Image" src="https://github.com/user-attachments/assets/f3128797-1142-4a45-8fa9-797b467a6822" />
