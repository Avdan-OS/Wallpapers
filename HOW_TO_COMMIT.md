## How to commit your files.

Inorder to commit your files you will either need [**a modern browser**](#using-a-browser-does-not-require-the-files-to-be-downloaded) or [**visual studio code with git**](#vscode-with-git) installed. (both require a PC)

# VSCode with Git

Using VSCode and Git is a easy way to add your files and commit them

1. Open VSCode 
2. Open the Terminal (Either its open already or open manually using Terminal > New Terminal)
3. Fork the Github project
4. Copy the project URL (THE FORKED ONE NOT THE OFFICIAL ONE!)    

![Where To Find Github URL](.tutorial/images/whereToFindGitURL.png)

5. After you did that go back to VSCode and go to the terminal.
6. (OPTIONAL) Create a new folder for the project (`$ mkdir projects` (works both in Windows and Linux))
7. Paste the command: `$ git clone <project url you copied>`
   
![Pasted command in terminal](.tutorial/images/gitCommandInTerminal.png)

8. Open the folder that git clone created (If you did the optional path its at `<folder you created via terminal>/design`).

    doing that will ask you for a confirmation, just click "I trust the Authrors"

![VSCode confirmation required](.tutorial/images/trustAuthors.png)

9. Paste your desired file you created into the fitting folder (wallpapers/community for example) 
10. once you completed that, open the git tab in VSCode

![Git Tab](.tutorial/images/gitTab.png)

11. In the message tab write a small message like "Added some wallpapers, 17/07/2022"
12. Press Commit
13. (IF NOT LOGGED IN) it will ask you for a authetification, follow the automatic process and accept the prompts
14. Press yes if it says "No Stashed Changes"
    
![No Stashed Changes](.tutorial/images/vscodeNoStashedChanges.png)

15. Press Sync
16. Done! now follow the "How to create a propper pull request" in the main readme.




# Using a browser (Does not require the files to be downloaded)