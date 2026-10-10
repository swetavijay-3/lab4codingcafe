1.--global means the setting applies to all git repositories for your user account.If that is left out,the settings run only to the current repository,provided you run the command inside a git repository.

2.In ls this is obtained README.md  week1  week2 
  while in ls -a this is obtained .  ..  .git  .venv  README.md  notes.md  notes.mdc  week1  week2
ls -a shows all files including hidden files(.git)

3.Git is offering to track roughly 4 files/folders: three files and one folder (week2). Nothing obviously looks unfamiliar.

4.The files inside the .venv/ folder disappeared from git status because .gitignore now tells Git to ignore them.

5.Yes, commit `.gitignore` because it contains rules telling Git which files to ignore. Committing it ensures everyone working on the project follows the same rules.

6.The two headings are working directory and staging area.README.md moved from the working directory to the staging area.It is now staged,ready to be committed

7.
