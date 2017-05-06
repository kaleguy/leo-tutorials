# Code Chunking

In the screenshot below, we've created a new node with a @clean directive with a file name. 
We've pasted the contents of the file into the node.

<img width="500" src="leo4.png" alt="ScreenShot">

This is a Vuejs component file, with three sections. We're going to break the 
sections out into separate nodes. First create a section name using double angle brackets.

<img width="500" src="leo5.png" alt="ScreenShot">

Now select the section name plus the code you want to put in a sub node.

<img width="500" src="leo6.png" alt="ScreenShot">

Enter Cmd-Shift-D to chunk the selected content into a subnode.

<img width="500" src="leo7.png" alt="ScreenShot">

Repeat this process with the other sections of the Vuejs component, now each has its own node. 

<img width="500" src="leo8.png" alt="ScreenShot">

This is a simple example, but using Leo it is possible to quickly break up a large,
complex set of code into manageable pieces. The target file is not affected,
and if the target file is changed in another program, Leo will update the appropriate nodes.
