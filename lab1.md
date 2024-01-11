`cd` with no arguments<br>
![Image](cd no args.png)<br>
working directory is `/home`<br>
Having no arguments didn't point to any directory for the `cd` command to open, so nothing happened<br>
It is not an error<br>

`cd lecture1` where `lecture1` is a directory
![Image](cd directory arg.png)
working directory is `/home`
`lecture1` is a directory that the `cd` command was directed to open, and this is what the command did
Not an error

`cd README` where `README` is a file
![Image](cd file arg.png)
working directory is `/home/lecture1`
`README` is a file and the `cd` command can't take a file as an argument
It is an error because `cd` isn't supposed to take files as arguments, just links to other directories within it



![Image](ls no args.png)

![Image](ls directory arg.png)

![Image](ls file arg.png)




![Image](cat no args.png)

![Image](cat directory arg.png)

![Image](cat file arg.png)
