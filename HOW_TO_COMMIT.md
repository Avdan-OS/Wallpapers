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

9. Drag and drop your desired file you created into the fitting folder (wallpapers/community for example) 

10. Add a new entry to the [Changelog](CHANGELOG.md) (Follow the given format)

11. once you completed that, open the git tab in VSCode

![Git Tab](.tutorial/images/gitTab.png)

12. In the message tab write a small message like "Added some wallpapers, XX.XX.XXXX"
13. Press Commit
14. (IF NOT LOGGED IN) it will ask you for a authetification, follow the automatic process and accept the prompts
15. Press yes if it says "No Stashed Changes"
    
![No Stashed Changes](.tutorial/images/vscodeNoStashedChanges.png)

16. Press Sync
17. Done! now follow the [How to create a push request](README.md#how-to-create-a-push-request) in the main readme.




# Using a browser (Does not require the files to be downloaded)

1. Open the Github project
2. Fork it
3. After doing that, you should see this page

![Github homepage](.tutorial/images/gitProjectHomepage.png)

4. Press "." (this will launch a browser only instane of VSCode)
5. You now should see this:

![VSCode browser](.tutorial/images/vscodeInBrowser.png)

6. Drag and drop your desired file you created into the fitting folder (wallpapers/community for example)
   The file you added should now show up and should be highlighted in a green color

![Highlighted file](.tutorial/images/fileUploadedHighlighted.png)

7. Add a new entry to the [Changelog](CHANGELOG.md) (Follow the given format)

8. Open the VSC (Git) tab

![Git tab in VSCode browser](.tutorial/images/gitTabOnline.png)

9. Give it a fitting name (Like "Adding some wallpapers, XX.XX.XXX")
10. Press the checkmark.
11. Done! now follow the [How to create a push request](README.md#how-to-create-a-push-request) in the main readme.