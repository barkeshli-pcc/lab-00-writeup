# Windows Instructions

- ## [Opening commandline](#win_opening_terminal)
- ## [Installing `git`](#win_installing_git)
- ## [Installing `cmake`](#win_installing_cmake)
- ## [Installing `MinGW`](#win_installing_mingw)

---

<br><br><br><br><br>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Opening the terminal ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)


> <img src="images/win_images/!com-00-open_command_line.png" alt="vscode_after_cloning" width="1000"/>

---

<br><br><br><br><br>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Installing git ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

## is `git` installed?

Let's check to see if `git` is installed on your system: type `git --version` at the commandline.

If you do not get a response similar to this, then you do not have `git` on your system and you have to install it.

> <img src="images/win_images/git-00-git_version.png" alt="vscode_after_cloning" width="1000"/>

<br>

## Download `git`

Download git from [here](https://git-scm.com/download/win). You should get an exe similar to this: `Git-2.30.0.2-64-bit.exe`<br><br>

> <img src="images/win_images/git-01-download_git_00.png" alt="vscode_after_cloning" width="1000"/>

<br>

## Install `git`

Open/run the executable, and follow the steps to install. You can safely stick with the **default options** for everything.<br>

And Install!<br>

> <img src="images/win_images/git-01-download_git_08png.png" alt="vscode_after_cloning" width="1000"/>

<br>

When it is done installing, click Finish. You may view release notes if you want.<br>

> <img src="images/win_images/git-01-download_git_12.png" alt="vscode_after_cloning" width="1000"/>

<br><br>

## Tell git who you are:

Give git your name and email address:

```
git config --global user.name "barkeshli, sassan"
git config --global user.email sxbarkeshli@pasadena.edu
```

<br>

## Check the version of the git again:

To make sure `git` is intalled correctly, run `git --version` again:<br><br>

> <img src="images/win_images/git-02-git_version.png" alt="vscode_after_cloning" width="1000"/>

<br>

<br><br><br><br><br><br>

<a name="win_installing_cmake"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Installing cmake ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

## is `cmake` installed?

Let's check to see if `cmake` is installed on your system: type `cmake --version` at the commandline.

If you do not get a response similar to this, then you do not have `cmake` on your system and you have to install it.<br><br>

> <img src="images/win_images/cm-02-cmake_version.png" alt="vscode_after_cloning" width="1000"/>

<br>

## Download `cmake`

Download cmake from [here](https://cmake.org/download/). Choose the Windows win64-x64 Installer. You should get an msi with a name similar to this: `cmake-3.19.4-win64-x64.msi`<br>

> <img src="images/win_images/cm-00-download_site.png" alt="vscode_after_cloning" width="1000"/>

<br>

## Install `cmake`

Open/run the executable, and follow the steps to install.  

> <img src="images/win_images/cm-01-download_00.png" alt="vscode_after_cloning" width="1000"/>

<br>

**Make sure** to select Add CMake to the system PATH for all users. You can create a Desktop icon if you want, but you will not need to use it for this class.  

> <img src="images/win_images/cm-01-download_03.png" alt="vscode_after_cloning" width="1000"/>

<br>

The default install location wshould be C:\Program Files\CMake\ <br>

> <img src="images/win_images/cm-01-download_04.png" alt="vscode_after_cloning" width="1000"/>

<br>

When it is done installing, click Finish.<br>

> <img src="images/win_images/cm-01-download_07.png" alt="vscode_after_cloning" width="1000"/>

<br>

## Check the version of the cmake again:

To make sure `cmake` is intalled correctly, run `cmake --version` again:
<br><br>

> <img src="images/win_images/cm-02-cmake_version.png" alt="vscode_after_cloning" width="1000"/>

<br>

---

# <BR><BR><BR><BR><BR>

<a name="win_installing_mingw"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Install MinGW ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

## is `MinGW` installed?

Let's check to see if `g++` is installed on your system: type `g++ --version` at the commandline.

If you do not get a response similar to this, then you do not have `g++` and/or `MinGW` on your system and you have to install it.<br><br>

> <img src="images/win_images/g++-00-g++_version.png" alt="vscode_after_cloning" width="1000"/>

<br>

## Download `MinGW`

Download cmake from [here](https://sourceforge.net/projects/mingw/files/). You should get an exe named similar to this: `mingw-get-setup.exe`<br><br>

## Install `MinGW`/`g++`

Open/run the executable, and follow the steps to install.<br>
The default Installation location should be C:/MinGW. Once again, you can add a Desktop shortcut, but it will not be neccesary for this class.<br>

> <img src="images/win_images/g++-01-download_02.png" alt="vscode_after_cloning" width="1000"/>

<br>

If you get a warning that MinGW is already installed, you can either reinstall and continue with this walkthrough or choose Run Now and skip to the steps below with the MinGW Install Manager.<br>

> <img src="images/win_images/g++-01-download_03.png" alt="vscode_after_cloning" width="1000"/>

<br>

When it is done installing, click Continue.<br>

> <img src="images/win_images/g++-01-download_06.png" alt="vscode_after_cloning" width="1000"/>

<br>

The **MinGW Installation Manager** should be opened up automatically. For this class, you will need mingw32-base, mingw-gcc-g++, and mingw23-gcc-objc.
<br><br>

> <img src="images/win_images/g++-02-selection_00.png" alt="vscode_after_cloning" width="1000"/>

<br>

To select a package for installation, right click on it in the menu and select Mark for Installation.<br>

> <img src="images/win_images/g++-02-selection_01.png" alt="vscode_after_cloning" width="1000"/>

<br>

Marked packages will look something like this:<br>

> <img src="images/win_images/g++-02-selection_02_zoom.png" alt="vscode_after_cloning" width="1000"/>

<br><br>

you **also** need to select the pthreads package from under <br>
All Packages -> MinGW Libraries<br>
Select only the **dev** version<br>

> <img src="images/win_images/99-01-pthread.png" alt="vscode_after_cloning" width="1000"/>

<br>

Once all neccesary packages have been marked, go to Installations > Apply Changes to install.<br>

> <img src="images/win_images/g++-02-selection_03.png" alt="vscode_after_cloning" width="1000"/>

<br>

Click Apply. This process will take a while.<br>

> <img src="images/win_images/g++-02-selection_04.png" alt="vscode_after_cloning" width="1000"/>

<br>

Once the changes are applied you may close the Installation Manager.<br>

> <img src="images/win_images/g++-02-selection_07.png" alt="vscode_after_cloning" width="1000"/>

<br><br>

## Add g++ as a System Variable and to your path

Search for "path" in the task bar search box. Open Edit the system environment variables.

> <img src="images/win_images/g++-03-path_00.png" alt="vscode_after_cloning" width="600"/>

<br>

Click on "Environment Variables..."

> <img src="images/win_images/g++-03-path_01.png" alt="vscode_after_cloning" width="600"/>

<br>

Add the path to the gcc and g++ executables to environment variables as shown below and press OK.<br>

> <img src="images/win_images/g++-03-path_02.png" alt="vscode_after_cloning" width="600"/>

<br>

Next, double click on the **user variable** Path (in the top half of the window). A window like this should pop up:

> <img src="images/win_images/g++-03-path_before.png" alt="vscode_after_cloning" width="600"/>

<br>

Click New, and enter C:\MinGW\bin to the text box. Click OK.<br>

> <img src="images/win_images/g++-03-path_after.png" alt="vscode_after_cloning" width="400"/>

<br>

Your environment and user variables should look like this after you are done:<br>

> <img src="images/win_images/g++-03-path_03.png" alt="vscode_after_cloning" width="400"/>

<br><br><br>

## Check the version of the g++ again:

To make sure `MinGW`/`g++` is intalled correctly, run `g++ --version` again. If the version output doesn't show, reboot your machine and try again.<br><br>

> <img src="images/win_images/g++-00-g++_version.png" alt="vscode_after_cloning" width="1000"/>

<br>

---

## Once all software has been installed, continue to the [next step](start_project.md)