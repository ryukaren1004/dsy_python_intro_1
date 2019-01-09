# Why should you learn to write programs?

Writing programs (or programming) is a very creative and rewarding activity. You can write programs for many reasons, ranging from making your living to solving a difficult data analysis problem to having fun to helping someone else solve a problem. This book assumes that everyone needs to know how to program, and that once you know how to program you will figure out what you want to do with your newfound skills.

We are surrounded in our daily lives with computers ranging from laptops to cell phones. We can think of these computers as our "personal assistants" who can take care of many things on our behalf. The hardware in our current-day computers is essentially built to continuously ask us the question, "What would you like me to do next?"

![alt text](./images/pda.svg)

As you install Python, make sure to check the "Add Python 3.5 to PATH" so that you can type python at the command line prompt to run Python.

Installing the Atom Text Editor
Please download and install Atom from this site:

http://atom.io

# Writing a Python 3 program with Atom on Windows-10
We have a short [step-by-step video](https://www.youtube.com/watch?v=uZbaYeYGYRQ&index=1&list=PLlRFEj9H3Oj7Bp8-DfGpfAfDBiblRfl5p) showing how to install Python 3 and Atom and write your first program.

# Windows Command Line Notes
When the command line starts up, you are in your "home" directory. Your home directory is different for each of the operating systems. In each of these examples, your logged in account should be used instead of your_login_account.

    Windows XP:             C:\Documents and Settings\your_login_account
    Windows Vista:          C:\Users\your_login_account
    Windows 7:              C:\Users\your_login_account
    Windows 10:             C:\Users\your_login_account

The command line prompt usually includes some clue as to where you are in the folder structure on your hard drive.
If you want to really figure out where you are, use the cd command with no parameters

    C:\Users\your_login_account> cd
    C:\Users\your_login_account

Where can you go?

Generally the first thing you want to do when you open a command line interface is to navigate to the right folder. Say you wanted to run a file from your desktop. The command is cd Desktop to get into the folder that is your Desktop. You can use the dir command to see which files are in the current directory and the cd .. command to go "up" a directory

Nifty Trick: On the cd command, you can partially type a folder name like Desktop and then press the TAB key and the system will auto-complete the folder name if you have typed enough that the system can accurately guess what you mean to type.

If you get Lost...

If you can't figure out what folder you are in and/or cannot figure out how to get to the folder you want to get to - simply close and re-open the Command Line / Terminal window. You will be back to your "home" directory - so you can start from a known location.

Some Cool Hints on the Windows Command Line Interface

If you click on the little icon in the upper-left of the command prompt window and select Preferences - you can set many things about the command line - probably the most important is to set the Command History Buffer Size to be 999.

# Running Your Python Program in the Command Line
To run your program in the command line you type at the command line prompt. Windows knows that files wthat end with a ".py" suffix are Python programs.

    python firstprog.py
or

    firstprog.py

Where firstprog.py is the name of the file containing your Python program. Make sure to use the cd command to be in the correct directory that contains your program file(s).
You can run your program over and over again in the command window. Hint: You can use the up-arrow key to scroll back through previous commands and re-execute them by pressing enter. This allows you to quickly edit and rerun your program to make and test changes.