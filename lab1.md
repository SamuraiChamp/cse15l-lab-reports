# Lab Report 1
## `cd` with no arguments
![Image](cd no args.png)<br>
working directory is `/home`<br>
Having no arguments didn't point to any directory for the `cd` command to open, so nothing happened<br>
It is not an error<br>

## `cd lecture1` where `lecture1` is a directory
![Image](cd directory arg.png)<br>
working directory is `/home`<br>
`lecture1` is a directory that the `cd` command was directed to open, and this is what the command did<br>
Not an error<br>

## `cd README` where `README` is a file
![Image](cd file arg.png)<br>
working directory is `/home/lecture1`<br>
`README` is a file and the `cd` command can't take a file as an argument<br>
It is an error because `cd` isn't supposed to take files as arguments, just links to other directories within it<br>

## `ls` with no arguments
![Image](ls no args.png)<br>
working directory is `/home`<br>
`ls` lists everything stored within the working directory<br>
No errors<br>

## `ls lecture1` where `lecture1` is a directory
![Image](ls directory arg.png)<br>
working directory is `/home`<br>
`ls lecture1` locates `lecture1` in the working directory and lists the contents of it<br>
No errors<br>

## `ls en-us.txt` where `en-us.txt` is a file
![Image](ls file arg.png)<br>
working directory is `/home/lecture1/messages`<br>
`ls en-us.txt` is called on the `en-us.txt` file which should just repeat the name of it since it isn't a directory<br>
No errors<br>

## `cat` with no arguments
![Image](cat no args.png)<br>
working directory is `/home`<br>
`cat` if given no inputs will read from the command line and repeat the text inputted by the user<br>
No errors<br>

## `cat lecture1` where `lecture1` is a directory
![Image](cat directory arg.png)<br>
working directory is `/home`<br>
`cat lecture1` uses the `lecture1` directory as an argument and the `cat` command isn't meant to take directories as inputs<br>
There is an error because `cat` is meant to read a file's contents and not access a directory<br>

## `cat README` where `README` is a file
![Image](cat file arg.png)<br>
working directory is `/home/lecture1`<br>
`cat README` accesses the `README` file and prints its context as text in the command line<br>
No errors<br>
