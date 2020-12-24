## "Operator, I'm in"

Yes indeed, let us explore a little more.
Lets check what files are currently in the directory. Again try out the following commands, thereafter I will explain what they do.

`ls`{{execute}}

`mkdir bigapple`{{execute}}

`ls`{{execute}}

`cd bigapple`{{execute}}

`pwd`{{execute}}

`nano smallfry.txt`{{execute}}

So first off we have the commad: `ls` - this lists all the files and folders in the current directory. It terminal should show nothing. So lets create a new folder called `bigapple`. That is what the command `mkdir bigapple` does. This creates a new folder called `bigapple`. Then we input the `ls` command again and you should see the newly created folder. However, we are not in the folder. To navigate to that folder we use the command: `cd bigapple`.
Then we checked our the current directory with the `pwd` command.
Then we created a new file called `smallfry.txt`. There a few ways to do this but we are going to use a text editor to create and write in the file we created. So then we input the command `nano smallfry.txt`. 

What does this command do? Well `nano` is the editor and `smallfry.txt` is a text file we want to create. A simple text editor pops up
once you input this command. You can now input in whatever you want. 

Try that out now, for example in the editor type out: `I like chips`. Then to save the the file press `CTRL`then`x`.
Then press `y` to save changes and then press `enter`. Check the file exists with the `ls` command.
Remember the `cat` command, lets try that out. Input the command `cat smallfry.txt` - what do you see?

Now lets delete the file, which is quite simple to do. Input the command `rm smallfry.txt` then check that with the `ls` command that the file should be gone.

Now lets go back to the previous directory. To do that input the command `cd ..` which takes you to the previous directory. Similarly `cd ../../` takes you
two directories back. Lastly `cd ~` takes you back to the first directory.

A few more commands. Lets say we want to rename a folder, for example `bigapple` to `bigsoup`. You can use the command `mv bigapple bigsoup`. The `mv` command
moves files or directories as well.

Lastly to remvove a folder use the command `rm -R bigsoup`.