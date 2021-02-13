# Mac Insructions</br>

- ## [Installing `git`](#mac_installing_git)</br>
- ## [Installing `cmake`](#mac_installing_cmake)</br>
- ## [Accepting the assignment](#mac_accepting_the_assignment)</br>
- ## [Project organization](#mac_project_organization)</br>

- ## [Quick edit, `status`, `add`, `commit`, & `push`](#mac_quick_edit_status_add_commit_n_push)</br>
- ## [Getting started with the project](#mac_getting_started_with_the_project)</br>
- ## [Writing tests](#mac_writing_tests)</br>
- ## [Completing the project](#mac_completing_the_project)

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

# <BR><BR><BR><BR><BR>

<a name="mac_accepting_the_assignment"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Accept the assignment ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

## Here is the **assignment link** for [CS3A](https://classroom.github.com/a/qidO1KYV) and here is the link for [CS8](https://classroom.github.com/a/DYb_nBnE)

# </br>

## Accept assignment page:

Once you click on the assignment link, we need you to _accept_ the assignment. This will create a repo under your github username.
But before you click and accept the assignment, let's look at a couple of things a bit more closely.

> <img src="images/lab0_images/a-00-accept_assignment.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Your repo name:

This is your repo name. The name of the assignment followed by your github name.

> <img src="images/lab0_images/a-01-your_repo_name.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Accept the assignment

You will _accept_ the assignment by clicking the green button.

> <img src="images/lab0_images/a-02-click_to_accept.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Your assignment repo being created.

Once you accept the assignment, github will begin to creat your assignment repo. You will see this page:

> <img src="images/lab0_images/a-03-waiting_for_setup.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Your assignment repo:

Give it a few seconds, and reload the page and you should see this:

> <img src="images/lab0_images/a-04-reload_to_update.png" alt="vscode_after_cloning" width="1000"/>

</br>

## look closer:

Take a closer look and youwill see the link to your repo. Click it and you will find your assignment repo:

> <img src="images/lab0_images/a-05-your_repo_address.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Your assignment repo:

Bookmark this page or know how to get here. We'll need to check in here soon.

> <img src="images/lab0_images/a-06-your-repo.png" alt="vscode_after_cloning" width="1000"/>

</br>

## The **Code** button:

The green button on the mid-right side that says **Code**, click it and that opens this box:

Click the little clipboard and that will copy the link into your clipboard so you can paste it in the next step. You will use this url to clone your repo:

> <img src="images/lab0_images/a-07-copy_clone_link.png" alt="vscode_after_cloning" width="1000"/>

</br>

## clone the assignment repo:

Before you can work on your project, you will need a local copy of the assignment. This is called **cloning** the repository.

First step is to `cd` into the fodler where you will be storing all your projects.

`cd` into your projects folder and clone your project there.

and then: `git clone [clone link] [destination_folder]`

That's what's happening here. I don't like my folder name to be `lab_00_barkeshli`. I like `lab_00`, so, I give it the new name and that clones the project into a folder named `lab_00`

> <img src="images/lab0_images/a-08-clone_and_rename.png" alt="vscode_after_cloning" width="1000"/>

</br>

## `cd` into this project folder:

> <img src="images/lab0_images/a-09-cd_into_project_folder.png" alt="vscode_after_cloning" width="1000"/>

</br>

## `code .`:

this will open VSCode and loads the current folder into it.

> <img src="images/lab0_images/a-10-open_vscode_here.png" alt="vscode_after_cloning" width="1000"/>

</br>

---

# <BR><BR><BR><BR><BR>

<a name="mac_project_organization"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Project Organization: ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

Once you have cloned the project and you open VSCode, this is what you will see:

> <img src="images/lab0_images/01-vscode_after_cloning.png" alt="vscode_after_cloning" width="1000"/>

</br>

## File system:

All the projects in this class will follow the same file organization.

On the left panel (Explorer, ) you will find the `main.cpp` on the root folder, and the three most important folders in this directory:

`_tests`: which holds your google test files. The grader will run these files to obtain your score. You will ignore `testA.cpp` for the most part. The bulk of your work will be done in `testB.cpp`.

`includes`: contains a folder for each of the libraries / classes your project depends on. In this starter code, you only have a `stub` folder that contains `stub.h` and `stub.cpp`. These files are `#include`d in `testB.cpp`

`build`: is where you go to build and run your project. This is where all your compiled and executable files will end up.

> <img src="images/lab0_images/02-vscode_file_structure.png" alt="vscode_after_cloning" width="200"/>

</br>

## A look at the test files:

### basic_test.cpp: My sample test goes here.

This is the placeholder file for a sample test file you wilkl be given for each and every project. The purpose of this file is to demonstrate the functionality of the project and for you to make sure that your function signatures and class declarations match the grader's expectations. (otherwise, your projects will not earn a score.)

### testB.cpp: Your tests go here

This is the file that will contain your tests of your own functions and classes. All your test fils that will demonstrate the correctness of your poject are housed here. Part of your grade relies on the quality and success of the tests in this file.

> <img src="images/lab0_images/03-basic_test_testB_generic.png" alt="vscode_after_cloning" width="1000"/>

</br>

## CMakeLists.txt

The github grader as well as your local Mac or linux systems will use the CMakeLists.txt file to build your project.

### List your cpp files here

the `CMakeLists.txt` file is what the cmake program looks at to know how to build your project. How the pieces fit together.

When you submit your code, you need to tell it what files are needed to build the test executables.

The grader will also use this file to build your project on the server side (once you submit - push your projects to github)

Please note that you will **only** make changes to the bottom half of this file.
It's worth mentioning that every **.cpp** file that is used in any of your test files (main, basic_test, testA, testB) will have to be listed here. Notice how the stub.cpp is listed under ADD_EXECUTABLE(testB...)

> <img src="images/lab0_images/04-cmakelists.png" alt="vscode_after_cloning" width="1000"/>

</br>

## stub.h, stub.cpp

Not too much to see here. The stub is used in testB to demonstrate how a function will be tested by the googletest framework in `testB.cpp`. All your functions and classes will be housed under their own folder (`stub/`, `array_functions/`, `vector/`, etc.) which will, in turn, go under the `includes/` folder.

> <img src="images/lab0_images/05-include_stub_h_cpp.png" alt="vscode_after_cloning" width="1000"/>

</br>

---

# <BR><BR><BR><BR><BR>

<a name="mac_quick_edit_status_add_commit_n_push"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Quick edit, `status`, `add`, `commit` & `push` ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

</br>

One of the main tasks in this class is tracking changes made to the project. We need to know what happened when and what changed. This is both for your peace of mind (helps you not lose your project accidentally,) and for me to track your progress throught he course.

We use **git** to track changes.

**Here**, we will make some small change to one of our files and walk through the entire process of tracking that change with `git`, just so you can get used to it.

## `git status`

let's run `git status`. look at the response: It says there are not changes as of yet. That's correct, isn't it. We have not made any changes.

> <img src="images/lab0_images/c-00-git_status_1.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Edit the README.md

Enter your name in the README.md and save it.

> <img src="images/lab0_images/c-01-edit_readme.png" alt="vscode_after_cloning" width="1000"/>

</br>

## `git status` again:

if you run `git status` again, you will see that git has kept track of our changes. this time, it says that the file `README.md` has changed. But it says that the file is not _staged_ for commit.

Think of it this way... There are four zones:
</br></br>

[changes not staged]

---- `git add`--->

[staged changes, but not committed]

---- `git commit`--->

[committed changes]

---- `git push`--->

[pushed, or synched with remote site]

You go from zone to zone by the commands listed above.

> <img src="images/lab0_images/c-02-git_status_2.png" alt="vscode_after_cloning" width="1000"/>

</br>

## `git add` and then, `git status` again:

In order to _stage_ the changes for `commit`, Enter `git add README.md`. This will stage the file.

do `get status` again. Now, you see that `README.md` has been _staged_

> <img src="images/lab0_images/c-03-git_add_status_again.png" alt="vscode_after_cloning" width="1000"/>

</br>

## `commit` your changes:

You `commit` your changes to permanently record these changes to `git`. If somehow you ruin your project (as we all have done from time to time,) you can _revert_ to this state of your project.

`commit`ting is like _saving_ your changes to `git`

Enter `git commit -m "[explain what you just did, in your own words]"`

Here,`-m` is a switch that tells `git` that you will be typing a message to document what this `commit` was for. We want this message to be concise and descriptive of the work that is being recorded.

Try typing in your own message in your own words.

> <img src="images/lab0_images/c-04-git_commit.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Has Github assignment repo changed?

Take a look at your assignment repo on your browser. You will see that eventhough you have committed your changes, Github does not know about them!

`commit`ting only records your changes on your local machine.

> <img src="images/lab0_images/d-00-commit_gh_has_not_changed.png" alt="vscode_after_cloning" width="1000"/>

</br>

## What is my local `branch` name?

If we want Github to know about our changes, we must `push` them to Github. But before you do, let's find out what our current _branch_ is.

For me, the branch name is `master` as evidenced by these images.

Your bash prompt on your terminal:

> <img src="images/lab0_images/d-02-git_prompt.png" alt="vscode_after_cloning" width="200"/>
> </br>

the branch name on your Github repo page:

> <img src="images/lab0_images/d-06-branch_name.png" alt="vscode_after_cloning" width="300"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; > <img src="images/lab0_images/d-06-branch_name_zoom.png" alt="vscode_after_cloning" width="300"/>

</br>

</br>

</br>

## `git push`:

Since my branch name is `master`, I will issue the command `git push origin master` which means push to `origin`, which is my github remote name, from `master` which is my local branch name. For you, your branch namge might be `main`, so, your commmand will be `git push origin main`:

If your command is successful, you will get a response similar to this:

> <img src="images/lab0_images/d-01-push_origin_master.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Now, Github knows about our changes:

Take a look at your project repo on Github. See how the changes you made to README.md shows on your repo:

> <img src="images/lab0_images/d-05-gh_changed.png" alt="vscode_after_cloning" width="1000"/>

</br>
</br>

## `commit` and `push` often:

Make sure you `commit` your changes after completion of **every** task. Remeber, `commit`s are the record of your progress. You will be graded on your commits. And push your changes frequently.
<BR><BR>
<BR><BR>
<BR><BR>
<BR><BR>

## Bonus: `git log`

Enter `git log` and see what the response is. What does this command do?

---

# <BR><BR><BR><BR><BR>

<a name="mac_getting_started_with_the_project"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Getting started with the project ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

## Find <a href="./basic_test.cpp" target="_blank">`basic_test.cpp`</a>

You will be supplied with a <a href="./basic_test.cpp" target="_blank">`basic_test.cpp`</a> file. You will copy this file and overwrite the existing _generic_ `basic_test.cpp` in your project folder. After this, you will **never** edit the `basic_test.cpp` file.

<a href="./basic_test.cpp" target="_blank">`basic_test.cpp`</a> demonstrtes the functionality of the project and gives you an opportunity to make sure your function signatures and class declarations match those of the grader.
You should be able to compile and run the `basic_test.cpp` with your functions.

Pay special attention to the `#include` path at the top. Your file structure has to be **exactly** the same as the one depicted here.

###### click <a href="./basic_test.cpp" target="_blank">here</a> to download basic_test.cpp if you have not already.

<br>

> <img src="images/lab0_images/06-basic_test_testA_copied.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Add a new folder to the `includes/` folder.

name this folder `array_functions`.

This is where you will add your `.h` and `.cpp` files

> <img src="images/lab0_images/07-add_array_function_folder.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Add two files to this folder.

Name these two files `array_functions.h` and `array_functions.cpp`

> <img src="images/lab0_images/08.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Add the function signatures.

add these function signatures to the `array_functions.h` file:

```
void _array_init(int a[], int size, int x=0);
void _append(int a[], int& size, int append_me);
int _find(const int a[], int size, int find_me);
int& _at(int a[], int size, int pos);
ostream& _print_array(const int a[], int size, ostream& outs = cout);

```

Normally, you will either be given these function signatures or you will _deduce_ them from the code in `basic_test.cpp`

> <img src="images/lab0_images/09-array_functions_h.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Write function _stubs_

Function stubs are just function signatures with a return statement if needed.

Function stubs are a quick way to get the project up and running. I find the students who adopt this method in their workflow have an easier time completing projects.

### TIP:

I normally copy the function signatures and paste them into the `.cpp` file. Then, I replace the `;` at the end of the line with braces (`{}`). Then, I add the returns whenever necessary.

> <img src="images/lab0_images/10-array_functions_cpp_stubs.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Open terminal:

If you are using VSCode, you can open the terminal by pressing [ctrl][`]

[`] is the key in the top left of the keyboard under [~]

Using the terminal in this way is very convenient.

> <img src="images/lab0_images/11-open_terminal.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Go to `build/` and run `cmake`:

`cd` into the `build/` folder, and from there, run `cmake ..`

This will run `cmake` on your _parent_ folder. (that's what `..` means. `cmake ..` means run `cmake` on my parent folder.)`cmake` creates a bunch of files and you do not want these files in the root folde of your project. Running `cmake` from `build/` will make sure all your auxilary files are created inside the `build/` folder.

Hopefully, your `cmake` will run without any problems and it will tell you that "Build files are written to `. . . build/`"

Now, we are ready to compile our project using `make`

> <img src="images/lab0_images/12-cmake_dot_dot.png" alt="vscode_after_cloning" width="1000"/>

</br>

## `make`

type `make` to compile your project:

If you followed these steps faithfully, you will have the same syntax errors that I had, namely that all those functions we defined in `array_functions.h` and `.cpp` are **undefined!**

We will spare you the suspense. The reason for this error is that we never added `array_functions.cpp` to our `CMakeLists.txt`. Remember that **all .cpp** files must be listed in the CMakeLists.txt under `ADD_EXECUTABLE`

> <img src="images/lab0_images/13-make.png" alt="vscode_after_cloning" width="1000"/>

</br>

## `make` errors, zoomed in:

Here is a closer, more readable look at the errors reported by `make`

> <img src="images/lab0_images/14-syntax erros.png" alt="vscode_after_cloning" width="1000"/>

</br>

## back at the `CMakeLists.txt`:

Notice that we are missing the `array_functions.cpp` from the `basic_test` `ADD_EXECUTABLE` statement:

So, let's add it...

> <img src="images/lab0_images/15-cmakelist_where to add.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Add `array_functions.cpp` to the `ADD_EXECUTABLE(basic_test... )`

**Do not** use commas to separate the files.

**Do NOT** include `.h` files.

Normally, **all** three executables will need all the `.cpp` files

> <img src="images/lab0_images/16-cmakelist_add_cpp.png" alt="vscode_after_cloning" width="1000"/>

</br>

## `make` again:

Let's run `make` again and pray that...

... and, we have more syntax errors. Default arguments can only be specified in the declration of the function and **not** in the definition.

So, we must remove all those default values for the defalut arguments on every function.

> <img src="images/lab0_images/17-fix_syntax_errors.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Fix the `_print_array` function...

> <img src="images/lab0_images/18-default_arg.png" alt="vscode_after_cloning" width="1000"/>

</br>

## by removing the default value `= cout`

> <img src="images/lab0_images/19-default_arg.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Same with `_array_init`:

> <img src="images/lab0_images/20-default_arg.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/lab0_images/21.png" alt="vscode_after_cloning" width="1000"/>

</br>

## `make` one more time:

and this time it will run successfully.

This is a huge step. We now have a working project eventhough our functions are basically empty.

You can even run the `basic_test` from the `bin/` directory. Of course this will not run satisfactorily. You will get mostly garbage. -afterall, we are running on stubs!- but it **does** run!!

> <img src="images/lab0_images/21x-make_run_basic_tet_with_empty_stubs.png" alt="vscode_after_cloning" width="1000"/>

</br>

## run `git status`, `add`, and `commit` with the message _success on make with stubs_

### The importance of having **regular** `commit`s in your project cannot be overstated. This is a large part of the evaluation of your project by me.

</br></br>

> <img src="images/lab0_images/22-git_add_commit.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Implement `_array_init` and `_print_array`. `testB.cpp` can be seen waiting to host the test functions.

Now, we can go in and implement the functions one by one and write tests for them. These tests will be written in the `testB.cpp` file.

</br>

> <img src="images/lab0_images/24-testB_before_edit.png" alt="vscode_after_cloning" width="1000"/>

</br>

---

# <BR><BR><BR><BR><BR>

<a name="mac_writing_tests"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Writing Tests: ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

## `testB`: our first test:

After implementing the \_array_init and \_print_array functions, we will write a simple test that will verify that the \_init function works as it should.

The test function is boolean. It returns `true` if the init function works properly and false otgherwise.

Call the `_array_init` function and then go through each and every cell and verify that each element is -1.

If you find one cell that is not -1, return false.

Note also that we return `true` at the end of the test function. I do this in every test function I write.

> <img src="images/lab0_images/25-test_init_array.png" alt="vscode_after_cloning" width="1000"/>

</br>

#The `TEST` function:

The `TEST` function is part of the googletest testing framework. To simplify our work, we always use the same format for the `TEST` function: Declare a `bool success` and assign it to the return value of the test function.

Then, compare `success` with `1` or `true`

A quick word about the two arguments of the `TEST` function:

The first is the name of the _test suit_ and the second is the name of this very test. Each test suit may contain multiple tests. Later, we will write another test for the `_append` function with the same first argument as this test: `TEST_ARRAY`. By the time we are done, the `TEST_ARRAY` test suite will have three individual tests.

Pay attention to the **naming conventions** for this course: The test suite will be in ALL CAPS with underscores between the words. The test names will be camel case and regular function names are all lower case with underscores.

> <img src="images/lab0_images/26.png" alt="vscode_after_cloning" width="1000"/>

</br>

## `make` and RUN!!

This time, we will run `make` successfully and then, we run the `testB` executable by typing `./bin/testB`

This means execute the file named `testB` that is located in the `bin` folder which is under the `current folder`. The bin folder is created by `make`

remember that `.` means current folder and is not optional. You **must** include the dot in the call to execute `testB`

This will display two successful test runs: one for the `stub` test that was already part of the project, and one for the `TestInit` that we just wrote.

This means that our test function returned `true`.

> <img src="images/lab0_images/27-make_run_testB.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Implement `_append` and `_at`:

We have thus far implemented `_array_init` and `print_array`. Let's implement `_append` and `_at` as well.

You will _borrow_ my code for this particular lab, but make sure you comment the code very well.

Once we have implemented `_append`, write the test for it in `testB.cpp`. Don't forget to add a `TEST( )` for the `test_append()` function.

> <img src="images/lab0_images/29_0_test_append.png" alt="vscode_after_cloning" width="1000"/>

</br>

Obviously, this is done in the `testB.cpp` file. Again, do not forget to add the `TEST( )` function for `test_at()`

Once again, you will _borrow_ my code for this particular lab, but make sure you comment the code very well.

> <img src="images/lab0_images/29_1_test_at.png" alt="vscode_after_cloning" width="1000"/>

</br>

## `make` and run `testB.cpp` again:

Let's `make` and run `testB` to make sure our `test_append` and `test_at` pass:

> <img src="images/lab0_images/30-PASSED_three_tests.png" alt="vscode_after_cloning" width="1000"/>

---

# <BR><BR><BR><BR><BR>

<a name="mac_completing_the_project"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Completing the project ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

## Implement the `_find()` function on your own

You will also write a `test_find()` function. Once you have implemented `_find()` and written the test function for it (don't forget to comment) you are ready to `make` and run `testB` once again.

Once you have successfully run `testB` with `_find`, you `git add ` and ` commit` your changes:

> <img src="images/lab0_images/32-add_commit.png" alt="vscode_after_cloning" width="1000"/>

</br>

<BR>

## Finally, we can run `basic_test.cpp`:

Now that we have implemented all the functions that are used in `basic_test.cpp`, we can `make` and run this file.

I cannot overemphasize how important it is for this test to be able to compile and run **without** your editing it in any way. If your project cannot compile and run `basic_test`, the grader will not be able to run your project.

> <img src="images/lab0_images/31-PASSED-basic_test.png" alt="vscode_after_cloning" width="1000"/>

</br>

## `git add` and the final `git commit`

Let's go back to the root directory by typing `cd ..` - remember that `..` means parent directory. `cd ..` means change directory to the parent.

My commit message will let me know what stage of the development I am in. I have just PASSED both the `basic_test` and `testB`

> <img src="images/lab0_images/33.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Autograder Status

You can keep track of the grading status of your project on the assigmment page. A yellow dot means that the tests are still being compiled and run by the autograder.This shouldn't take more than a minute or two. You can refresh the page to update the status. A green checkmark neans that all your tests have passed. A red x means that at least one test failed.

<br/><br/>

> <img src="images/win_images/test-04_reslts_github_02.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-04_reslts_github_04.png" alt="vscode_after_cloning" width="1000"/>

</br>

To see a more in depth output of the autograder test runs, click on the Details link:

<br/><br/>

> <img src="images/win_images/test-04_reslts_github_05.png" alt="vscode_after_cloning" width="1000"/>

</br>

It will take you to this page:
<br/><br/>

> <img src="images/win_images/test-04_reslts_github_07.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-04_reslts_github_08.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-04_reslts_github_10_zoom.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-04_reslts_github_11_zoom.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-04_reslts_github_12.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-04_reslts_github_13.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-04_reslts_github_15.png" alt="vscode_after_cloning" width="1000"/>
