Mail Flood!
=================================

mailflood-2.1.1

This program is written by Uriah Christensen. If you have a copy of this program, feel free to modify it for your needs. If you distribute, please make sure the original source code is what is distributed. 

Running the program:

You can run it by opening a terminal to “<Path>/mailflood” and running the command:
python3 ./mailflood.py

Installation:
You need to have python and sendmail on your computer to run the program. Most linux/unix distros should have the first one. You may need to install sendmail. See your distribution for details on setting this up. On Ubuntu, you can use the command “sudo apt-get install sendmail”. On Windows, I suggest installing CYGwin. Make sure the packages for python, and sendmail are being installed on the setup. Look up how to start the sendmail deamon once its installed one windows. 

That is all. Now you can run the program.

==================================================
Change log:
mailflood-2.1.1
-Added a check for the number of emails entry. Checks to see if the entry is an integer. If not, a window pops up that tells you to put in a number, and deletes the entry field. there is an error in the console after you close the main window when you have put a non-integer in  number field, but it doesnt effect the function of the program. 

mailflood-2.1.0
-Rewrote the program using Tkinter for the GUI, fixing GTK+ 3 portability issue with PyGobject import
-No longer supporting Python 2.x. Only using Python 3.x  

mailflood-2.0.2
-No longer exits autmatically after sending the emails, allowing for use multiple times
-Resets all fields when done running for easy indication of completion
-Fixed bug that left python running in the background after closing the GUI.

mailflood-2.0.1
-Removed printing to standard output debugging, as it was no longer needed after 1.0
-Added a From field so you can spoof other email address you want besides the same email as the recipient.
