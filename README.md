# Python-Dictionary
![image](https://github.com/TheRonnie/Python-Dictionary-Using-Tkinter/assets/98576788/6a8538b8-f7cf-4dba-b130-04328a16e841)

 A simple English dictionary application built using Python and Tkinter.

In my code is a Tkinter-based GUI application that serves as an English Dictionary. It provides functionality to add new words, find the meanings of existing words, update word meanings, and exit the application gracefully. Let's break down the functionality of each button:

1. **Add a new word (Button b1):**
   - Prompts the user to input a word and its meaning.
   - Checks if the word already exists in the "words.txt" file.
   - If the word exists, it prints its meaning and prompts the user to update the meaning.
   - If the word doesn't exist, it adds the word and its meaning to the "words.txt" file.
   - Prints a message indicating the success of the operation.

2. **Find the meaning (Button b2):**
   - Prompts the user to input a word.
   - Searches for the word in the "words.txt" file.
   - If the word is found, it prints its meaning.
   - If the word is not found, it prints a message indicating that the word is not present.

3. **Update a word (Button b3):**
   - Prompts the user to input a word.
   - Searches for the word in the "words.txt" file.
   - If the word is found, it prints its meaning and prompts the user to update the meaning.
   - If the user chooses to update the meaning, it prompts for the new meaning and updates the word's meaning in the "words.txt" file.
   - If the user chooses not to update the meaning, it returns to the main menu.

4. **Exit (Button b4):**
   - Closes the Tkinter window, terminating the application.

Overall, your code provides a basic user interface for interacting with the English Dictionary functionalities. Users can add, search, and update word meanings through the graphical interface. Additionally, it handles user input and file operations appropriately.
