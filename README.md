Simple Text Editor
This is a basic text editor program written in C that allows users to perform various file operations within the current directory. Users can open, save, delete, append content to files, list files in the directory, get help information, and exit the editor.

Features
Open: Open an existing text file from the current directory.
Save: Save content to a file or create a new file if it doesn't exist.
Delete: Delete a file from the current directory.
Append: Add content to the end of an existing file.
List: View a list of all files in the current directory.
Help: Display available commands and their descriptions.
Exit: Close the text editor and save any changes made.
Getting Started

Compile: Compile the C code using a C compiler (e.g., GCC).
bash
Copy code
./text_editor

Commands
Open: Use the command open to open a file by providing its name.
Save: Save or create a file using the save command followed by the filename.
Delete: Remove a file using the delete command followed by the filename.
Append: Append content to a file using the append command followed by the filename.
List: Get a list of all files in the current directory by typing list.
Help: Access the help information using the help command.
Exit: Exit the text editor using the exit command.

Notes
The editor operates within the current directory where the program is executed.
Content appended to a file is added at the end of the existing content.
Use Ctrl+Z (Windows) or Ctrl+D (Unix-like systems) to indicate the end of input for save and append operations.


Limitations
1)Limited error handling for file operations.
2)Input restrictions for filenames and file content length.
3)Assumes basic text files without advanced formatting.
