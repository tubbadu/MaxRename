# MaxRename

a command line tool to rename multiple files in the command line

## Requirements

> python3
> 
> os # should be already installed
> 
> sys # should be already installed
> 
> glob # should be already installed

## Preparaton

if you already added a bin folder to your path, skip this passage:

+ create a ~/bin or ~/.bin folder

+ open ~/.profile with a text editor

+ add this to the bottom line:
  
  ```bash
  PATH=$PATH":$HOME/bin" # or /.bin
  ```

then:

+ copy `maxrename` to that folder:
  
  ```bash
  mv maxrename ~/bin/maxrename
  ```

restart your session or launch ```source .profile``` and it will be right to be used.

## Usage

```
user@user:~$ maxrename /full/path/to/file1 /full/path/to/file2 /full/path/to/file3
Insert new name (the '#' char will be replaced with crescent numbers):
your_new_name#.your_extension


for other run maxrename -h because i'm too tired to write here the other commands
```

and voilà!

## TODO:

* 
