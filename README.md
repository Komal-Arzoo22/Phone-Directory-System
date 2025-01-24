# Phone-Directory-System
Project Title: Phone Directory System 
Overview: A simple phone directory system implemented in C++ that allows users to add, delete, search, and display contacts.
Installation Instructions: 
1. Clone the repository to your local machine.
2. Compile the code using a C++ compiler (e.g., g++).
3. Run the executable file.
Usage Guide:
1. Run the program and select an option from the menu.
2. Follow the prompts to perform the desired action (e.g., add contact, delete contact, search contact).
3. Use the "Undo Last Action" option to revert the last change made to the directory.
Results:
The program displays the results of each action, including the updated contact list and any errors that may occur.
Features
- Add contacts with name and phone number
- Delete contacts by name or phone number
- Search contacts by name or phone number
- Display all contacts
- Undo last action
- Queue operation (FIFO) to retrieve the first added contact
Code Organization:
src/:- contact_book.cpp: Implementation of the ContactBook class.
     - contact_book.h: Header file for the ContactBook class.
     - main.cpp: Main entry point of the program.
data/: contacts.txt: File to store contacts.
results/:
requirements.txt:Note: Since this is a C++ project, there is no requirements.txt file. Instead, you would typically list dependencies in a build configuration file (e.g., CMakeLists.txt for CMake).


