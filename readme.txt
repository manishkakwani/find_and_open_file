Here's a fun little ruby script I put together.  I have a folder where I store all my ebooks, and i very frequently use some books as references (linux books, programming ruby, etc.).  It was annoying to use the GUI to always click through the same directories and then visually scan for files.  I thought it would be great to write a script that has the command line find a list of files based on a regex you give, and then allow you to select the number of the one you want to open.  Now I just type in a few keystrokes and I'm good to go.  I'll probably even create some aliases to open up very common files.

I learned a lot of cool things from working on this, including how to store scripts and make them executable, calling bash commands from within a ruby program, and working with command line arguments. 

----------------------------------
most recent version of script will always be stored in /usr/local/bin, named "fo", to be executable for all users 
