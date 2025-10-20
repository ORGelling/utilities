# Make a simple file structure with this program

This is a relatively simple perl script, mimicing Frank Brokken's makeclass
program. Call it and it will ask for a begin and end number and will create
all the directories and basic files (metadata.txt, order.txt and
ex[dirNr]info.txt) for you in the style of how the exercises of his course
shuold be handed in. It should not overwrite existing files or directories of 
those names. 

Put it in /usr/bin/ and give it proper perms (chmod -x makedirs) and it should
be good to go!

An example of the output is shown inside the example directory.

https://github.com/ORGelling/Makedirs For the main repo. Will use submodules 
soon(ish) (tm)
