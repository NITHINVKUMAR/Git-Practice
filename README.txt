git init —> initialises an empty git repository it also creates and .git folder that has all the relevent logic
to manage the versions of your project.

9)git restore --staged <filename> —> It pulls the file out of the staging area and puts it back 
into the working area. The actual code changes inside the file remain untouched; 
it just tells Git, "Don't include this file in the next commit yet."