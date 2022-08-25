Author's note: WIP

<a name="win_quick_edit_status_add_commit_n_push"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Quick edit, `status`, `add`, `commit` & `push` ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

<br>

One of the main tasks in this class is tracking changes made to the project. We need to know what happened when and what changed. This is both for your peace of mind (helps you not lose your project accidentally,) and for me to track your progress throught he course.

We use **git** to track changes.

**Here**, we will make some small change to one of our files and walk through the entire process of tracking that change with `git`, just so you can get used to it.

<br>

## `git status`

let's run `git status`. look at the response: It says there are not changes as of yet. That's correct, isn't it. We have not made any changes.
<br><br>

> <img src="images/win_images/Quick-00-quick_edit_00.png" alt="vscode_after_cloning" width="1000"/>

<br>

## Edit the README.md

Enter your name in the README.md and save it.
<br><br>

> <img src="images/win_images/Quick-00-quick_edit_01.png" alt="vscode_after_cloning" width="1000"/>

<br>

## `git status` again:

if you run `git status` again, you will see that git has kept track of our changes. this time, it says that the file `README.md` has changed. But it says that the file is not _staged_ for commit.

Think of it this way... There are four zones:
<br><br>

[changes not staged]

---- `git add`--->

[staged changes, but not committed]

---- `git commit`--->

[committed changes]

---- `git push`--->

[pushed, or synched with remote site]

You go from zone to zone by the commands listed above.

<br><br>

> <img src="images/win_images/Quick-00-quick_edit_02.png" alt="vscode_after_cloning" width="1000"/>

<br>

## `git add` and then, `git status` again:

In order to _stage_ the changes for `commit`, Enter `git add README.md`. This will stage the file.

do `get status` again. Now, you see that `README.md` has been _staged_

<br><br>

> <img src="images/win_images/Quick-00-quick_edit_03.png" alt="vscode_after_cloning" width="1000"/>

<br>

## `commit` your changes:

You `commit` your changes to permanently record these changes to `git`. If somehow you ruin your project (as we all have done from time to time,) you can _revert_ to this state of your project.

`commit`ting is like _saving_ your changes to `git`

Enter `git commit -m "[explain what you just did, in your own words]"`

Here,`-m` is a switch that tells `git` that you will be typing a message to document what this `commit` was for. We want this message to be concise and descriptive of the work that is being recorded.

Try typing in your own message in your own words.

<br><br>

> <img src="images/win_images/Quick-00-quick_edit_04.png" alt="vscode_after_cloning" width="1000"/>
> <br>

## Has Github assignment repo changed?

Take a look at your assignment repo on your browser. You will see that eventhough you have committed your changes, Github does not know about them!

`commit`ting only records your changes on your local machine.
<br>
<br>

## What is my local `branch` name?

If we want Github to know about our changes, we must `push` them to Github. But before you do, let's find out what our current _branch_ is.

For me, the branch name is `master` as evidenced by these images.

Your bash prompt on your terminal:

<br><br>

> <img src="images/win_images/Quick-00-quick_edit_05.png" alt="vscode_after_cloning" width="1000"/>

<br>

## Zoomed in:

`git branch` will tell you the name of our local branch. Try it.

<br><br>

> <img src="images/win_images/Quick-00-quick_edit_06_zoom.png" alt="vscode_after_cloning" width="1000"/>

<br>

## `git push`:

Since my branch name is `master`, I will issue the command `git push origin master` which means push to `origin`, which is my github remote name, from `master` which is my local branch name. For you, your branch namge might be `main`, so, your commmand will be `git push origin main`:

If your command is successful, you will get a response similar to this:

<br><br>

> <img src="images/win_images/Quick-00-quick_edit_06.png" alt="vscode_after_cloning" width="1000"/>

<br>

## Now, Github knows about our changes:

Take a look at your project repo on Github. See how the changes you made to README.md shows on your repo:
<br><br>

> <img src="images/lab0_images/d-05-gh_changed.png" alt="vscode_after_cloning" width="1000"/>

<br>
<br>

## `commit` and `push` often:

Make sure you `commit` your changes after completion of **every** task. Remeber, `commit`s are the record of your progress. You will be graded on your commits. And push your changes frequently.
<BR><BR>
<BR><BR>

## Bonus: `git log`

Enter `git log` and see what the response is. What does this command do?

---

<br><br><br><br><br>

# Git commands:

### `git clone`:

Downloads the files in your github repository onto your local machine

![](clone.png)

**`git clone <repo link>`** will create a folder that is named after the repo in your directory and put all the files from online into it.

### `git status`:

Shows which files git is tracking and which files have been added to a commit
**git status**

This is how it will look if you haven't edited any files<br>
![](images\git\status-no-change.png)

This is how it will look if you have edited files, but not added them<br>
![](images\git\status-no-add.png)

This is how it woll look when you have added a change<br>
![](images\git\status-after-add.png)

### `git add`:

Adds selected files to be committed.

**`git add <filename>`** adds the specified file to be committed. Note: You do not need to write the <> when using this command, just the filename
**`git add .`** adds all uncommitted files to the commit
**`git add \*.cpp`** adds all files of type cpp to be committed

### `git commit`:

“Saves” the current state of all the added files in your local repository. Only files added at the time this command is run will be “saved”

**`git commit -m “comment”`** creates a commit with a descriptive comment or message. It is a good idea to explain what you’ve accomplished when committing. An example of a good comment would be: “Implemented string class”

![](images\git\commit-message.png)

**`git commit`** creates a commit without a comment. Your command prompt may open up a text editor like vim or emacs for you to leave a commit message. If you are not familiar with command line text editors, this can be confusing. To exit out of vim press **esc**, and enter **`:!q` (and enter)** to exit. To exit out of emacs, press **ctrl+x** then **ctrl+c**.

### `git push`:

Uploads all your local repo commits to the github website. Even if you have committed work, it will not be available on github until you push it. Note: Once a commit has been pushed to github, only the time/date it was committed will be shown, not the time/date it was pushed<br>

![](images\git\push.png)

### `.gitignore`

There may be files you will never want to add to a commit. Like files generated by cmake or googletest when you build your project. You can tell git to ignore them by adding the names of those files (or directories) to a file named **`.gitignore`** in the highest level of your repository. There should be one file per line.

You can tell git to ignore certian types of files by adding **\*`.<filetype>`** as a line in your .gitignore.

# Filesystem standards:

Using the command prompt/terminal is similar to travelling through your filesystem in the normal File Explorer or Finder. When you first open your terminal, you will be in the home directory. This is usually your user folder (contains Documents, Desktop, etc.). From there you can travel to different folders within the file system.

When traversing your file system from the command line, there are certain shortcuts and commands that are good to know.

### `ls/dir`:

**`ls/dir`** shows the folders and files in your current directory. ls is used on Linux and Mac, and dir is for Windows.

**`ls/dir -a`** will show hidden files in the directory

![](images\git\ls.png)

### `cd`:

Stands for “change directory”. This is how to move between different folders in the command line. This only works for folders. You cannot open a .txt file or any other type of file with cd.

From your home directory you may want to do **`cd Documents`** to move to your Documents folder.

You don’t have to travel from one folder to another by moving one level at a time. cd will take you to the end of a path that you give it.

Let’s say your project folder called pointers is in Documents/cs3/ch2. You can get there quickly by entering **`cd Documents/cs3/ch2/pointers`** into the terminal.

**`cd ..`** will take you up a level from your current position in the file structure. From the previous example, you would use this if you are in your ch2 file and want to move to cs3.

![](images\git\cd.png)

**`cd`** without a path will take you back to your home directory on Linux/Mac, and will print your current path on Windows
