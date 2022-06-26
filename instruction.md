![logo](https://totaku.ru/wordpress-markdown-druzia-navsieghda/featured-image.png)

# Instruction of using Git & Markdown language

## Markdown language syntax

-   **using ** text ** to the bold font**

-   _using _ text _ for the italic font_
-   using "#" or ##" for the header styles

*   ~~using ~~ Text ~~ for a strikethrough font~~
*   For using that fonts dont't put any space between font's simbols and text: ^some text^, where ^ is font's simbol

-   using "\*" for the unnamed lists

*   using 1, 2, 3 ect for the named lists

![logo](https://cdn.filestackcontent.com/6yJPbkQ4SnybLJPKPLXP)

## Git's commands

### In the beginning some basic commands

First of all you have to execute the following global config commands, so enter:

1. **git config --global user.name "user's name"** for register in Git under your name
2. **git config --global user.email <user's_email@example.com>** to register in Git your email

-   Enter following commands:
-   **git init** to initializing the local repository and tracking its files (you will have to enter _git add_ for start tracking each new file)

### Basic commands

-   1. **Warning! Save the file.**
-   2. **git add** to add a new commit
-   3. **git commit -m <_comment_>** to create a new commit with massage of it
-   **git commit -am <_comment_>** to add changes and create a new commit with massage of it
-   **git add.** for adding all files
-   **git commit --amend -m <_new commit_>** to edit commit

### Some useful commands

-   **git diff** to find out the difference between the current file and the committed file
-   **git log** to display the history of all commits with their hash codes
-   **git status** to get information from git about its current state
-   **git --version** to get information from git about its current version

### Branches

-   **git checkout** version_number
-   **git checkout master** return to the working commit

## Several Global commands

### Enter:

-   **git config --global user.name "UserName"** to register in Git under your name
-   **git config --global user.email "UserEmail"** to register in Git your email
-   **git config --global --replace-all user.name "UserName"** to replace user's name
-   **git config --global --replace-all user.email "UserEmail"** to replace user's email
