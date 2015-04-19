# DairyApp

Summary:

Contains a password protected linear diary, and search method for finding occurences of words. This is achieved three fold. A linked list that contains each entry as it is added linearly, and a binary search tree that holds an array of pointers for each unique word, where the pointers lead to entries where the word occurs. So if you want to see entries where you used the word "cat" you can easily search for it. All of these entries, along with a one time chosen pasword will be saved to a text file, and read back into the program upon starting, so it doesn't delete everything each time. The Diary entries will contain a date, and a message of any length.


Interface:

This program's interface will be fairly simple, and is pretty much identical to what we've done before in class. It will display a menu like this first

=======Password=======
Enter Your Password

and then, if entered correctly, will lead to this menu


======Main Menu=====
1. New Entry
2. Search for Word
3. Review All Entries
4. Search by Date
3. Quit

Dependancies:

There will be no extra libraries needed for this program, just a functioning copy of Code Block software. Theoretically it should work in any CPP ready programming software cappable of building multiple files simultaneously.


System Requirements:

Since CodeBlocks can work on Linux/Microsoft/Apple there should be no system requirements.

Contributors:


Open Issuses/Bugs:


