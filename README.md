# Online-Linux-Code-Editor
This is a flask-based python code editor for the programming of linux/windows/mac computers remotely from the web browser of another device

INSTALLATION:
It can be installed using git clone, and the code editor can be accsessed by going to the browser of another(or the same) device and typing in the ip adress or local host.

REQUIREMENTS: Flask, python 3, working internet, a computer to program and a computer to program from.

HOW TO USE:
It consists of a place to enter in code and a terminal. The terminal has two places to enter text. The first is where you enter commands like 'ls -l' or 'touch code.py'. 
If you type in 'open' in the first panel and a file name in the second panel, you open the file you typed in, and it is displayed in the textarea where you can enter code. 
If you type in 'save' in the first panel, and a file name in the second panel, you can save the text in the textarea for code to the filename you typed in. 
In chrome, you can do things like control-f to search, or enter in recently typed in terminal commands, or open the developer javascript console by pressing control-shift-i.

PLANNED FEATURES:
Syntax highlighting, hopefully in the next week.
An iframe to go to programming-related webpages, that starts off showing usage instructions.
A dedicated 'run' button.
A dedecated 'save' button.
A better UI.

DEVELOPMENT TEAM
I (Jacob) am solely developing the main features, but my brother (Nathan) has agreed to help with the css of the IDE.
