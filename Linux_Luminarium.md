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

