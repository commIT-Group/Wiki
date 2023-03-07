# Wiki
instructions on how to do things on GitHub

## How to contribute code to a project
To contribute your code to a group project, you need to clone a repo first to your local machine. It's also possible to work in GitHub Codespaces (online).
After cloning, you either select a specific development branch, or create a new one. Rules for naming branches will be [here](). (at some point) <!-- write rules, add link -->

<!-- convert this to a linked table of contents -->
tl;dr
1. Clone
2. Branch
3. Code
4. Pull request
5. Code review
6. Merge
________________

## How to clone a project

### 1. Go to the project page
e.g. [this one](https://github.com/commIT-Group/demo-repository). You can use this demo repository to test things out.

### 2. Click on the ```<>code``` button

![](https://github.com/commIT-Group/Wiki/blob/main/Cloning_01.png)

### 3. From the dropdown menu select one of the options: 
- a. copy the command, paste into command line, execute
- b. open with GitHub Desktop
- c. Download ZIP file.
  
![](https://github.com/commIT-Group/Wiki/blob/main/Cloning_02.png)

Choose the option that works best for you.

### 4. Select a local folder to store the cloned project
### 5. Done!

_____________
## How to create a branch: GitHub, option 1 (not recommended)

Branching can be done in a number of ways. Here is an example how to do it from the level of a GitHub repo. Option 1.

### 1. Go to the project page
e.g. [this one](https://github.com/commIT-Group/demo-repository). You can use this demo repository to test things out.

### 2. Click on the tab with the ```main``` branch name.
It opens up a dialog that allows you to switch to other existing branches, but also allows to create a new one. This option offers less control in regards to the branching point.

### 3. Enter a name for a branch in the textbox
### 4. Click on "create branch: [name]".
![](https://github.com/commIT-Group/Wiki/blob/main/Branching_01_a.png)
_____________
## How to create a branch: GitHub, option 2 (recommended)

Branching can be done in a number of ways. Here is an example how to do it from the level of a GitHub repo. Option 2.

### 1. Go to the project page
e.g. [this one](https://github.com/commIT-Group/demo-repository). You can use this demo repository to test things out.

### 2. Click on the branch icon (second tile).
![](https://github.com/commIT-Group/Wiki/blob/main/Branching_02_a.png)

### 3. New screen opens up. It looks like this:
![](https://github.com/commIT-Group/Wiki/blob/main/Branching_02_b.png)

Click on the green button: "Create a new branch".
### 4. This opens a popup.
![](https://github.com/commIT-Group/Wiki/blob/main/Branching_02_c.png)

Fill in the branch name, select branch source and click the green button. Done!

_____________
## How to create a branch: Command line (recommended)

Branching can also be done properly, from the command line / terminal.

### 1. Make sure you are in the repo.

You can check where you are in a local file repository using the ```pwd``` command. It should print working directory (aka filepath).
### 2. Check which branch is currently active using the command: ```git branch```. 
It should list all the branches that are in a certain repository. A * will appear next to the currently active branch.
### 3. Create a new branch using the command: ```git branch [name-of-the-new-branch]``` 
(skip the square brackets, don't use spaces). It will create a new branch at the current commit.
### 4. To switch to a new branch, use the command: ```git checkout [name-of-the-branch]```. 
This command will switch your code changes to the branch you specified.
