# NOTES-APP

Notes App
---(Java File I/O)

 # A simple text-based Notes Manager created in Java using File I/O.
This project lets you write, append, and view notes stored in a text file (notes.txt).

# Features

 Implements FileWriter, FileReader, and BufferedReader.
 Create new notes (overwrite existing ones).
 Add notes without removing old entries.
 Display all stored notes.
 Error handling with try-with-resources.

# Tools & Concepts Applied

 Java SE
 File I/O (FileWriter, FileReader, BufferedReader)
 Exception handling (IOException, FileNotFoundException)
 VS Code / Command Line

# Project Structure

* NotesApp.java → Main program
* notes.txt → File where notes are stored

# How to Run

1. Download or clone the repository.
2. Open the terminal in the project directory.
3. Compile and run:

   bash
   javac NotesApp.java
   java NotesApp
   

# Sample Menu


---- Notes App -----
1. Write a new note (overwrite)
2. Add a note (append)
3. View all notes
4. Exit


# Sample Output

```
----Notes App ---
1. Write a new note (overwrite)
2. Add a note (append)
3. View all notes
4. Exit
Enter your choice: 1
Enter note: Today I have Eye Check up
Note saved successfully!

------ Notes App ------
1. Write a new note (overwrite)
2. Add a note (append)
3. View all notes
4. Exit
Enter your choice: 1
Enter note: tomorrow i have to attend a marriage
Note saved successfully!

----- Notes App -----
1. Write a new note (overwrite)
2. Add a note (append)
3. View all notes
4. Exit
Enter your choice: 2
Enter note: in sirumugai
Note saved successfully!

------Notes App ------
1. Write a new note (overwrite)
2. Add a note (append)
3. View all notes
4. Exit
Enter your choice: 3

--- Saved Notes ---
tomorrow i have to attend a marriage
in sirumugai
-------------------

----- Notes App ------
1. Write a new note (overwrite)
2. Add a note (append)
3. View all notes
4. Exit
Enter your choice: 4
Exiting... Goodbye!




Thank you..!
