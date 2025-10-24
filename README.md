# Java Notes App

## Objective
A simple console-based Notes Manager built in Java that allows users to write and view notes.  
This project demonstrates basic File I/O operations using FileReader, FileWriter, and BufferedReader.

## Technologies Used
- Java  
- VS Code or Eclipse  
- FileReader, FileWriter, BufferedReader  
- Exception Handling  

## Features
- Add new notes and save them in a text file  
- View all saved notes anytime  
- Notes remain saved even after program closes  
- Uses try-with-resources for automatic file closing  
- Handles exceptions safely  

## How It Works
1. User gets a simple menu:  
   - Write a new note  
   - View all notes  
   - Exit  
2. Notes are saved in a file named `notes.txt`.  
3. The program reads data from the file line by line using BufferedReader.

## How to Run
1. Open terminal in your project folder.  
2. Compile the code:  
3. Run the program:  java NotesApp
4.  Follow the menu options to add or view notes.
5.  ## Example Output
===== NOTES APP =====

Write a new note

View all notes

Exit
Enter your choice: 1
Enter your note: Practiced File I/O in Java!
Note saved successfully!

===== NOTES APP =====

Write a new note

View all notes

Exit
Enter your choice: 2

----- Saved Notes -----


