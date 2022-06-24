![logo](https://totaku.ru/wordpress-markdown-druzia-navsieghda/featured-image.png)

# Instruction of using Git & Markdown language

## Markdown language & Git console commands

-   **using ** text ** to the bold font**

-   _using _ text _ for the italic font_
-   using "#" or ##" for the header styles

*   ~~using ~~ Text ~~ for a strikethrough font~~
*   For using that fonts dont't put any space between font's simbols and text: ^some text^, where ^ is font's simbol

-   using "\*" for the unnamed lists

*   using 1, 2, 3 ect for the named lists

![logo](https://cdn.filestackcontent.com/6yJPbkQ4SnybLJPKPLXP)

## Basic Git's commands

First of all you have to execute the following global config commands, so enter:

1. **git config --global user.name "user's name"** for register in Git under your name
2. **git config --global user.email <user's_email@example.com>** for register in Git your email

-   Enter following commands:
-   **git init** for initialization tracking in the required directory

*   1. **Warning! Save the file.**
*   2. **git add** for add a new commit
*   3. **git commit -m <_comment_>** for adding a massage of the new commit
*   **git add.** for adding all files
*   **git commit -am <_comment_>**
*   **git commit --amend -m <_new commit_>** for edit commit
*   **git diff** for know the differences of the versions
*   **git log** of you need know the history of differences
*   **git checkout** version_number
*   **git checkout master** return to the working commit
*   **git status** if you need know the status of Git
*   **git --version** for find out of the version of the Git program

# Several Global commands

### Enter:

-   **git config --global user.name "UserName"** for register in Git under your name
-   **git config --global user.email "UserEmail"** for register in Git your email
-   **git config --global --replace-all user.name "UserName"** for replace user's name
-   **git config --global --replace-all user.email "UserEmail"** for replace user's email
