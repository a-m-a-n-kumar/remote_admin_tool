Remote Administration Tool

This tool is made using these two python programs that facilitates remote code execution.

The listner.py program runs on attacker's computer

The backdoor.py program runs on victim's computer

To make a real trojan file i.e, an .exe file, you have to convert the backdoor.py program to an .exe file using pyinstaller

But first, to establish the connection between two systems, you have to enter your(attacker's) ip address as well as port number in both the programs.

Then use pyinstaller to convert backdoor.py to an .exe file.

After that, you can execute this .exe file in victim's computer.

When you execute this .exe file, a copy of this file will be made into the windows registery, which will execute this file every time you restart the computer.

After that, it will continously try to connect to attcker's computer until it achieves a connection to the attacker's computer.

For this, you have to execute listner.py program in your(attacker's) computer.

When executed, it will show "connection established" message followed by victim's pc ip address.

Now it will prompt like this >>

Now here you can enter any windows command and it will execute without any problem.

To upload a file from attacker's computer to victim's computer, type: upload filename(this file should be there in your present working directory)

To download a file from victim's computer to attacker's computer, type: download filename.

To capture the webcam of victim's computer, type: webcam.

You will see a filename named snapxxx xxxx.png. This file is of captured webcam of victim's computer.

Please note that these two python files are for educational purpose only, and i will not be responsible for and damage occured(so execute on your own risk).

