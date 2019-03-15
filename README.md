# 42project
A bash script that sets up the basic structure of a 42 Silicon valley project.  
The structure looks like this:  

                                                   foo
                             /               /              \             \
                         srcs            includes          Makefile        author
                     /        \            /
                  libft      foo.c      foo.h
                  
#### Installation
`git clone https://github.com/cmicheledelaney/42project`  
Add the 42project script to your path or create a bin and add it to your path if you don't have the permissions. Run this in
your shell:  
`mkdir ~/bin`  
Add this line to your .bashrc/.zshrc/.profile:  
`export PATH="$PATH:~/bin"`  
Move the script into the bin directory:  
`mv 42project/42project ~/bin`  
Add the executable bit:  
`chmod +x ~/bin/42project`  
Depending on where you want to store the Makefile template or if you want to use another one, change lines 14 and 15 accordingly. By default it clones my libft, feel free to change the URL in line 12 to the URL of your libft.

#### Run
To run the script just enter:  
`42project foo`    
and it creates a project called foo.
