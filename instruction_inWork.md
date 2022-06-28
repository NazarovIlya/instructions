![logo](resource\md.png)

# Instruction of using Git & Markdown language

## Markdown language syntax

### Titles

# title 1

Using "#" for title of 1 level

## title 2

Using "##" for title of 2 level

### title 3

Using "###" for title of 3 level

#### title 4

Using "####" for title of 4 level

##### title 5

Using "#####" for title of 5 level

###### title 6

Using "######" for title of 6 level

### Text

-   Using ** or \_\_ for the **bold font\*\*
-   Using * or \_ for the *italic font\*
-   Using \~\~ for a ~~strikethrough font~~

*   Using \*\*\* or \*\*\_ for the **_bold strikethrough font_**

-   For using that fonts dont't put any space between font's simbols (\*, \_) and text: ^some text^, where ^ is font's simbol

### Blockquote

Citation blocks are created using the symbol >
> This is a blockquote. It is usually rendered indented and with a different background color.

### Lists

Use - or \* to create a buletted list:

-   This is a parent list
-   parent bulleted list item 1
    -   this is nested list of first level
    -   nested list of first level item 1
    -   nested list of first level item 2
        -   this is nested list of second level
        -   nested list of second level item 1
        -   nested list of second level item 2
    -   nested list of first level item 3
    -   nested list of first level item 4
-   parent list item 1
-   the end of bulleted list

    Use numbers (1, 2, 3, ect) to create numbered list:

1. This is a parent numbered list
    1. this is nested list of first level
    2. list of first level item 1
    3. list of first level item 2
        1. this is nested list of second level
        2. nested list of second level item 1
        3. nested list of second level item 2
    4. list of first level item 3
    5. list of first level item 4
2. parent list item 1
3. parent list item 2
4. the end of numbered list

### Links

-   Use the constraction: \[link text\]\(http://some_link\) to paste the link
-   For an article that adds a link to another article in the same directory use: \[link text\]\(article-name.md\)
-   For an article that adds a link to an article in the parent directory of the current directory use: \[link text\]\(../article-name.md\)
-   For an article to which a link to an article is added in a subdirectory of the current directory use: \[link text\]\(directory/article-name.md\)
-   For an article to which a link to an article is added in a subdirectory of the parent directory of the current directory use: \[link text\]\(../directory/article-name.md\)

### Images

**_Also see [guide for Markdown](https://docs.microsoft.com/ru-ru/contribute/markdown-reference)_**

![logo](resource\git.jpg)

## Git's commands

First of all you have to execute the following global config commands, so enter:

1. **git config --global user.name "user's name"** for register in Git under your name
2. **git config --global user.email <user's_email@example.com>** to register in Git your email

-   Enter following commands:
-   **git init** to initializing the local repository and tracking its files (you will have to enter _git add_ for start tracking each new file)

### Basic commands

-   1. **Warning! Save the file.**
-   2. **git add** to add a new commit
-   3. **git commit -m "_comment_"** to create a new commit with massage of it
-   **git commit -am "_comment_"** to add changes and create a new commit with massage of it
-   **git add .** for adding all files
-   **git commit --amend -m "_new commit_"** to edit commit
-   **git checkout commit_hash** commit_hash
-   **git checkout master** return to the master commit

### Some useful commands

-   **git diff** to find out the difference between the current file and the committed file
-   **git log** to display the history of all commits with their hash codes

*   **git log --graph** to display a tree of commits

-   **git status** to get information from git about its current state
-   **git --version** to get information from git about its current version

### Branches

-   **git branch** to display the list of all branchers
-   **git branch new_branch_name** to create a new branch

*   **git checkout branch_name** to go to another branch
*   **git checkout master** to return to the master branch

-   **git merge another_branch_name** to merge the current branch with another one
-   **git branch -d branch_name** to delete the branch

## Several Global commands

### Enter:

-   **git config --global user.name "UserName"** to register in Git under your name
-   **git config --global user.email "UserEmail"** to register in Git your email
-   **git config --global --replace-all user.name "UserName"** to replace user's name
-   **git config --global --replace-all user.email "UserEmail"** to replace user's email
