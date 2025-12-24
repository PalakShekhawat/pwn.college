# Hello Hackers
## 1.Intro to Commands
Entering `hello` gave the flag.
## 2.Intro to Arguments
Learnt about `echo` command. <br>
It is used to print text in shell. <br>
eg. `echo Hello hackers` will print Hello hackers
## 3.Command History
The shell saves a history of every command invoked,we can scroll through those saved commands with the up/down arrow keys.

# Pondering Paths
## 1.The Root
The path that begins with `/` is called an `absolute path`.
## 2.Position thy self
a.Command `cd` is used for changing current working directory. <br>
eg. `cd Desktop` changes current directory to Desktop in case directory named Desktop exists.
<br>

b.Command `~` tell the current path where shell located.
The expansion of ~ is an absolute path.
## 3.Implicit Relative Paths
`Implicit Relative path` is the path that does not start at root. eg. `challenge/run` in this question.
## 4.Explicit Relative Paths
`Exlicit Relative Paths` With `./` ,Linux looks in your current folder. eg.`./run`

#  Comprehending Commands
## 1.`cat`
Used for reading out files.<br>
cat will concatenate multiple files if provided multiple arguments. <br>
For example:`cat file1 file2`

## 2.cat absolute paths
Eg.`cat /challenge/DESCRIPTION.md`

## 3.`grep`
Eg.`grep SEARCH_STRING /path/to/file`

## 4.Comparing files
`diff` compares two files line by line and shows you exactly what's different between them.

## 5.Listing Files
`ls` is used for listing files in given directory.

## 6.`touch`
Used for creating new files.Syntax for the same is `touch newfile`.

## 7.Removing files
`rm` is used for deleting files.

## 8.Moving files
`mv` is used for moving files.<br>
Syntax: `mv your-file location`

## 9.Copying files
`cp` is used to move the file to new location as well keep the original.<br>
Eg. `cp file new-file`.

## 10.Hidden files
Command `ls -a` is used for listing all the files starting with `.` alongwith rest of the files.

## 11.Making directories
`mkdir newdir` is used for making new directory.

## 12.Finding files
Syntax of `find` command id `find [options] [path] [expression]`.<br>
Path specifies where to start (defaults to current directory .), and expression defines search criteria like -name "filename".
## 13.Linking files
Symlinks (symbolic links) are special files in Linux that act like shortcuts, pointing to another file or directory via a path reference.
Create: ln -s /target /symlink (target first, then link name).<br>
Trick programs: Replace expected file with symlink to real target (e.g., ln -s /flag /home/hacker/not-the-flag).<br>
Verify: ls -l (shows ->), file (shows "symbolic link to").<br>
