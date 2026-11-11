1./home/sweta_vijay/coding-cafe/week2

2.The main difference is that ls lists only visible files and directories, while ls -a lists all files and directories, including hidden ones.
   When it was ls the return line was notes.md and when it was ls -a .  ..  notes.md was the return line.

3.-rw-r--r-- 1 sweta_vijay sweta_vijay 292 Aug 27 19:04 notes.md
   This is the return line of ls -l
   Its first column means file permission and file type.I have the permission to read and edit it while others can only read the content. 

4.It works because it is a relative path.It points to a location relative to the current working directory. It does not start with a forward slash (/). Because i am sitting in a folder that contains coding-cafe, typing coding-cafe/week2 tells Bash to look inside the coding-cafe folder right here.

5.mv README-backup.md week1 moves README-backup.md into the week1 directory while mv README-backup.md old-readme.md renames README-backup.md to old-readme.md inside the week2 folder.

6.17 folders are there on my path.

7./usr/bin/python3

8.It is the same because most default Linux setups install python3 in /usr/bin/python3.

9.Command 'pyton3' not found, did you mean:
  command 'python3' from deb python3 (3.14.3-0ubuntu2)
Try: sudo apt install <deb name> 
The shell is telling you that it searched every directory listed in my system's PATH variable, but it could not find an executable program named pyton3

10.Because filenames starting with a dot are hidden in Linux by default, the plain ls command filters out .venv, while ls -a reveals all files including hidden ones.

11.(.venv) starts to appear at the beginning of prompt.

12./home/sweta_vijay/coding-cafe/week2/.venv/bin/python3 is the isolated virtual environment Python while ./usr/bin/python3is the global system Python installation.This tells that running source .venv/bin/activate modified your shell's PATH environment variable by prepending(adding to the very beginning)the path to your virtual environment's bin/ directory.

13.Package            Version
------------------ ---------
certifi            2026.7.22
charset-normalizer 3.5.1
idna               3.19
pip                25.1.1
requests           2.34.2
urllib3            2.7.0
This is the second list and everything except pip25.1.1 is not there in the first list.

14./usr/bin/python3 
It goes back to normal or universal environment from isolated virtual environment.

15.It opens a manual page for ls command.It has name and synopsis,description,flag and options and so on which gives a complete reference for how to use ls.

16.CTRL+C sends an interrupt signal to the process telling it to stop while CTRL+D sends an End-Of-File takes you back to the prompt.
