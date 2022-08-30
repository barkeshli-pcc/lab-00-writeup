# Mac Insructions</br>

- ## [Installing `git`](#mac_installing_git)</br>
- ## [Installing `cmake`](#mac_installing_cmake)</br>

# <BR><BR><BR><BR><BR>

# <BR><BR><BR><BR><BR>

<a name="mac_installing_git"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) installing git ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

You may have to install git.
use `homebrew` to install git.

<br/><br/>

## Tell git who you are:

Once git is installed, you may need to let it know who you are: Give git your name and email address:

```
git config --global user.name "barkeshli, sassan"
git config --global user.email sxbarkeshli@pasadena.edu

```

# <BR><BR><BR><BR><BR>

<a name="mac_installing_cmake"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) installing cmake ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

## is `cmake` installed?

Let's check to see if `cmake` is installed on your system: type `cmake --version` at the commandline.

If you do not get a response similar to this, then you do not have `cmake` on your system and you have to install it.

> <img src="images/lab0_images/b-00-cmake_version.png" alt="vscode_after_cloning" width="1000"/>

</br>

## install `cmake`

We use `homebrew` to install `cmake`:

```
brew install cmake
```

This will go on and on...

> <img src="images/lab0_images/b-01-brew_install_cmake_1.png" alt="vscode_after_cloning" width="1000"/>

</br>

... and on...

</br>

> <img src="images/lab0_images/b-01-brew_install_cmake_2.png" alt="vscode_after_cloning" width="1000"/>

</br>

... and on...

</br>

> <img src="images/lab0_images/b-01-brew_install_cmake_3.png" alt="vscode_after_cloning" width="1000"/>

</br>

... and on...

</br>

> Finally, cmake is installed!
> <img src="images/lab0_images/b-01-brew_install_cmake_4.png" alt="vscode_after_cloning" width="1000"/>

</br>

## check the version of the cmake again:

To make sure `cmake` is intalled correctly, run `cmake --version` again:

> <img src="images/lab0_images/b-00-cmake_version.png" alt="vscode_after_cloning" width="1000"/>

</br>

---

## Once everything is installed, you can move on to the [next step](start_project.md)