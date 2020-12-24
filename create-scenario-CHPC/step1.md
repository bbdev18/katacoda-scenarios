Wow, whats going on here. We have three windows. The far left one is you tutorial section, the top right is the folder and editor window, and the bottom right is the bash terminal where `$` sign is showing. Where do you begin?

## Task 1
Let us play around with a few commands and then I will explain what they all do.
In this tutorial you can click on the `grey` command and it will actually execute in the terminal or you can type it out and then press `enter`.
For example, go ahead and click on the following command `click me`{{execute}}. You will see that the command `click me` was input into
the terminal.

Try out the following commands:

`whoami`{{execute}}

`pwd`{{execute}}

`cat /etc/os-release`{{execute}}

`date`{{execute}}

So what did these all do?

The input the command `whoami` allows you to to see who is the operator, it should be `root` - not like the tree :)
This just tells you that the operator of the terminal your in is called `root` and has admin rights, i.e. you have all the power to play around here.

Then the input the command: `pwd`, which should show `/root`, stands `print working directory`. This shows you your current working directory where all your files and folders are located.

Now how is this terminal running? Behind the scenes there is operating system (OS) that is running the terminal. That is what input the command: `cat /etc/os-release` tells us. You should see a lot information but the most useful is the following `NAME="Ubuntu"` which tells you you are running an Ubunut OS.

Lastly, the `date` command is pretty straight forward - it tells you the current date and time.

One last thing. Lets have a look at the command `cat /etc/os-release` in more detail.

The `cat` command - stands for concatonate - which just displays information in a file in the terminal. Then the `/etc/os-release` has two parts. The second part is where `os-release` is the file itself and `/etc` is the folder where the file resides itself. 

We will go into more depth on folder and file structure later.


