# D2-dclone-notificator
This simple python script calls data from diablo2.io diablo clone progression tracker for all regions (non-ladder, softcore), displays the progression in real time (updated every 90 seconds), and raises an alarm (text and a beep) when the progression gets sufficiently high (4 or higher) on any of the regions. It also features a primitive anti-trolling system.

The python script should work on Windows, OSX, or Linux. A batch file is provided for Windows.

Please note that: 1) this is a first draft, 2) that I have not been able to test this thoroughly, and 3) that I am not an expert programmer. May contain bugs! 

# How do I use it? (hard difficulty; browse lower for medium)
You simply run the script on a command line and leave it open. Close it by closing the window. Or use the batch file.

You may need to install *requests* module.

# I don't know how any of this works! (mediocre difficulty; browse lower for easy)
If you are unfamiliar with github, just go to the main repository page (https://github.com/Kalle-Koskinen/D2-dclone-notificator), click the green "Code" -button, and select download the ZIP file. The ZIP file contains the script d2dclone_notifier.py. MAKE SURE you put the batch (.bat) file *d2dclone_notifier.bat* to the same directory as the script! Create a shortcut if u need to launch from elsewhere.

If you are unfamiliar with running python scripts, easy instructions can be found for installing python here (https://codeigo.com/python/installing-python).

Then you will need to install the *requests* -module before running the script. This can be done *after installing python* by:
1) Open a command prompt
2) type *pip install requests*

You can now run the script by clicking on the batch file (d2dclone_notifier.bat) or its shortcut. Or you can run the script from the command line as instructed here (https://codeigo.com/python/run-python-script-on-windows).

Don't be scared, it should only take a few minutes!

# What?! (easy difficulty)

It is impossible to learn a language by speaking when you don't know even the basic words. No worries, here is the easiest way to install: https://github.com/Kalle-Koskinen/D2-dclone-notificator/tree/Kalle-Koskinen-Ez-Inst

# I want to use this for ladder/hardcore
At this point you would have to slightly edit the code to do that. You can do that by opening the script in a text editor, and in the beginning of the script, changing *league* (softcore/hardcore) and *ladder* (ladder/non-ladder) parameters. For league, "1" is hardcore and "2" is softcore (quotation marks included). For ladder, "1" is ladder and "2" is non-ladder (quotation marks included).

# Acknowledgments 
Data courtesy of diablo2.io, thank you!
Thank you WMAlleg for the batch file and feedback!
Thank you Masgalor for the adding multi-platform support!
