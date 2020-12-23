Wow, whats going on - a blank string with a `$` sign. Where do I begin?

## Task 1
Lets first check who is there?

Input the command: `whoami`

to see who is the operator, it should be `root` - not like the tree :)

This just tells you that the operator of the terminal your in is called `root` and has admin rights, i.e. you have all the power to play around here.

Now lets see where we are ?

Input the command: `pwd`, this should say `/root`
This `pwd` stands for `print working directory`. So this shows your current working directory where all your files and folders are located.

So what is this - this is a linux terminal where we will be working. Behind the scenes there is operating system (OS) that is running the terminal.

Lets check what OS we are running.

Input the command: `cat /etc/os-release`{{execute}}

You should see a lot information but the more useful is the following:
`NAME="Ubuntu"`

Lets have a look at the command we just What does this do?

`cat` - stands for concatonate - which just displays information in a file in the terminal

Then the `/etc/os-release`, where `os-release` is the file itself and `/etc` is the folder where the file resides itself. 

We will go into more depth on folder and file structure later.

## Task 2
Lets check what files are currently in the directory.

Input the commad: `ls` - this lists all the files and folders in the current directory. It should be empty.

So lets create a new folder called `bigapple`.

Input the command: `mkdir bigapple`

This creates a new folder called `bigapple`. Input the `ls` command again and you should see the newly created folder.

However, we are not in the folder. To navigate to that folder Input the command: `cd bigapple`

Now Input the `pwd` command and see how the directory has changed.

Now lets create a file. There a few ways to do this but we are going to use a text editor to create and write in the file we created.

So now Input the command `nano smallfry.txt`

What does this command do? Well `nano` is the editor and `smallfry.txt` is a text file we want to create. A simple text editor pops up
once you input this command. You can now Input in whatever you want, for example: `I like chips`. Then to save the the file press `CTRL`then`x`.
Then press `y` to save changes and then press `enter`. Check the file exists with the `ls` command.
Remember the `cat` command, lets try that out. Input the command `cat smallfry.txt` - what do you see?

Now lets delete the file, which is quite simple to do. Input the command `rm smallfry.txt` then check that with the `ls` command that the file should be gone.

Now lets go back to the previous directory. To do that input the command `cd ..` which takes you to the previous directory. Similarly `cd ../../` takes you
two directories back. Lastly `cd ~` takes you back to the first directory.

A few more commands. Lets say we want to rename a folder, for example `bigapple` to `bigsoup`. You can use the command `mv bigapple bigsoup`. The `mv` command
moves files or directories as well.

Lastly to remvove a folder use the command `rm -R bigsoup`.


## Task 3

First lets check what version of python we are running. Input the command `python3 --version`, note depending on how python was setup you can also use `python --version`. It should show `Python 3.6.9`, great lets jump in.

Input the command `python3`, a python terminal should appear.

Lets start off with some variables and simple maths functions.

Input `x = 40`

Input `y = 2`

Input `answer_to_the_question_of_life = x + y`

Input `print(answer_to_the_question_of_life)`

Input `40+2`

Input `print(40+2)`

Input `name = wabbit`

Input `print(name)`

## Task 4

Let do some useful things. First off let us have a look at conditions

Input `x = 42`

Input:

```
    if x > 40:
        print(`Yes x is greater than 42`)
       else:
        print(`No x is not greater than 42`)
```

And a loops, lets look at a for loop.

Input:

```
for i in range(10):
    print(i)


## Task 5
