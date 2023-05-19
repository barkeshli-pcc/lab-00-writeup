# Windows Instructions

- ## [Installing `git`](#win-installing-git--)
- ## [Installing `cmake`](#win-installing-cmake)
- ## [Installing `MinGW`](#win-installing-mingw)

---


# Installing git  <img src="images/win_images/Git-Icon-1788C.png" alt="git icon" width="25"/>


**Grab the latest git setup from** [here](https://gitforwindows.org). |  The ***default option*** for everything is perfectly fine, just keep clicking next.
:-------------------------:|:-------------------------:
<img src="images/win_images/git-dl-page.png" width="500" >  |  <img src="images/win_images/git-installed.png" width="440">


#### Ensure that `git` was installed successfully:
<br>

Run `git --version` in your command prompt:<br>

> <img src="images/win_images/git-install-check.png" alt="vscode_after_cloning" width="500"/>
<br>

## Configure git:

The steps in this section are very important.

First, let git know who you are, set your global name and email address in your command prompt, this only needs to be done once.
You can paste commands into your Command Prompt by right clicking.

```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```
This is important because every git commit you make will have this information baked into it. This is your identity.

If you like you may also check that your name and email were set correctly with `git config --get user.name` and `git config --get user.email`

#### Personal access tokens:
**Very important:** You will not be able to clone your repositories without first setting up a GitHub Personal Access Token. This is key that grants access to all your repositories, so be very careful with it.

Go to `github.com`, click your profile picture on the top right, click on `settings`. On the sidebar of the next page click `Developer settings` at the very bottom. At the bottom of the sidebar on the next page, click `personal access tokens`

Go to your profile settings   |  Go to `Developer Settings` | Create a `classic` token
:-------------------------:|:-------------------------:|:-------------------------:
<img src="images/win_images/github-settings.png" alt="vscode_after_cloning" width="230" height="600"/>  |  <img src="images/win_images/dev-settings-github.png" alt="vscode_after_cloning" width="200" height="600"/> |  <img src="images/win_images/create-token.png" alt="vscode_after_cloning" width="320" height="600"/>



| <img src="images/win_images/generate-new-token.png" alt="vscode_after_cloning" width="810" />  |
| :----------------------------------------: |
|      **Generate a new token**     |

| <img src="images/win_images/token-access.png" alt="vscode_after_cloning" width="810"/>   |
| :----------------------------------------: |
|      **check the `repo` box, leave all the boxes below unchecked, scroll down and click `Generate token`**   |



#### Finally, here is your token, this is the first and last time GitHub is going to show it to you, so put it in a secure folder or write it down on paper for future access.
<img src="images/win_images/generated-token.png" alt="vscode_after_cloning" width="800">

## Cloning a repository


The first time you attempt to clone one of your own repos you will be met with this prompt  |  Go to the `Token` tab and paste in your token
:-------------------------:|:-------------------------:
<img src="images/win_images/token-prompt.png" alt="vscode_after_cloning" width="650" >  |  <img src="images/win_images/token-paste.png" alt="vscode_after_cloning" width="400">

**After doing this once you will have permissions to clone repos unprompted.**

<br>

<a name="win_installing_cmake"></a>

# Installing cmake <img src="images/win_images/CMake-logo-triangle-high-res.png" alt="cmake icon" width="25"/>


### Download `cmake`

Download cmake from [here](https://cmake.org/download/). Choose the `Windows win64-x64 Installer`. You should get an msi with a name similar to this: `cmake-3.19.4-win64-x64.msi`<br>

> <img src="images/win_images/cmake-dl-page.png" alt="vscode_after_cloning" width="1000"/>

<br>

You may blindly click through the setup wizard, except for setting the path  |  Important: Make sure to select `Add CMake PATH for all users`
:-------------------------:|:-------------------------:
<img src="images/win_images/cm-01-download_00.png" alt="vscode_after_cloning" width="500"/> |  <img src="images/win_images/cm-01-download_03.png" alt="vscode_after_cloning" width="510" />

### Ensure that cmake was installed successfully:

To make sure `cmake` is intalled correctly, run `cmake --version`:
<br>

> <img src="images/win_images/cmake-version-check.png" alt="vscode_after_cloning" width="600"/>

If you see something like this, you're good to go!

<br>

---


<a name="win_installing_mingw"></a>

# Installing MinGW <img src="images/win_images/logo01.png" alt="mingw icon" width="25"/>


## Download `MinGW`

Download MinGW from [here](https://github.com/niXman/mingw-builds-binaries/releases). Download the release in below screenshot
> <img src="images/win_images/mingw-64.png" alt="64 mingw release" width="800"/>

Once downloaded use your favorite archive manager(e.g WinRAR, 7-Zip) to extract the archive straight to your C:\ drive
> <img src="images/win_images/mingw-extract.png" alt="Extract the release, technically it can go anywhere you like, just set the path in the next step" width="700"/>



## Set your path environment variable <img src="images/win_images/cpp-logo.png" alt="cpp icon" width="20"/>


Search for "path" in the task bar search box. |  Click `Environment Variables` |
:-------------------------:|:-------------------------:|
<img src="images/win_images/system-vars.png" alt="vscode_after_cloning" width="600">   |  <img src="images/win_images/enviro-vars.png" alt="vscode_after_cloning" width="600" />

Select `Path` variable and click `Edit`| Click `New` and paste in your `MinGW` path `C:\mingw64\bin`
:-------------------------:|:-------------------------:
 <img src="images/win_images/edit-path.png" alt="vscode_after_cloning" width="600" > |  <img src="images/win_images/new-path.png" alt="vscode_after_cloning" width="600"/>

Click `ok` and exit all the system environment windows

Verify the path was set correctly with `g++ --version` and `gdb --version`
> <img src="images/win_images/cpp-verify-install.png" alt="vscode_after_cloning" width="600"/>

If you see that you're all set to start the lab!


---

## Once all software has been installed, continue to the [next step](start_project.md)
