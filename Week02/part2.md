Part 2
1. What does the man command do? Type in man rm. How do you scroll and get out?
Use the arrow key to scroll. Type in `q` to quit

2. Look at the man page for ls. What does the -l flag do? What does the -a flag do?
`-l` 
> It lists the total sum of all the file and (The lowercase letter ``ell''.)  List in long format.  (See below.)  A total sum for all the file sizes is output on a line before the long listing.


`-a` list all files including the ones whose names begin with a dot(.)


3. Type the following command to download and save the contents of google.com: curl https://www.google.com > google.html

4. Use less to look at the contents of google.html.
5. Look at the man page for less. Read the section on /pattern. Search for the text hplogo in the google.html file.


6. How do you jump between words in the terminal?

7. How do you get to the end of a line in terminal?
8. How do you move your cursor to the beginning in terminal?
`cmd`+left arrow key

9. How do you delete a word (without pressing backspace multiple times) in terminal?
`Ctrl+W`
kill the whole line `Ctrl+U`

10. What is the difference between a terminal and shell?
A terminal is a program that runs shell, it's an interface. 

11. What is an absolute path?
An absolute path starts from home directory.

12.What is an relative path?
An relative path is the path that relative to the directory the user is currently in.

13.What is a flag? Give three examples of flags you have used.
A flag is an option we could pass to a command. I imagine under the hood, a flag is a parameter that a programm receieves that leads to different output.


14.What do the r and f flags do with the rm command?

`rm -r` is the equivalent to `-R` which removes a directory even it is not empty. 

`-f` flag stands for "force"? It attempts to remove files without prompting for confirmation. 