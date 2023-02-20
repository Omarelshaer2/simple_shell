# a simple shell rebuild :
This is a simple UNIX command interpreter written as part of the Alx software engineering course. For more information about Alx, visit (https://www.alxafrica.com/).

### Environment :
Upon invocation, this shell receives and copies the environment of the parent process in which it was executed. This environment is an array of *name-value* strings describing variables in the format *NAME=VALUE*. A few key environmental variables are:

#### HOME
The home directory of the current user and the default directory argument for the **cd** builtin command.

#### PWD
The current working directory as set by the **cd** command.

#### OLDPWD
The previous working directory as set by the **cd** command.

#### PATH
A colon-separated list of directories in which the shell looks for commands. A null directory name in the path (represented by any of two adjacent colons, an initial colon, or a trailing colon) indicates the current directory.

#### cd
  * Usage: `cd [DIRECTORY]`
  * Changes the current directory of the process to `DIRECTORY`.
  * If no argument is given, the command is interpreted as `cd $HOME`.
  * If the argument `-` is given, the command is interpreted as `cd $OLDPWD` and the pathname of the new working directory is printed to standad output.
  * If the argument, `--` is given, the command is interpreted as `cd $OLDPWD` but the pathname of the new working directory is not printed.
  * The environment variables `PWD` and `OLDPWD` are updated after a change of directory.

## Authors :

* Omar Elshaer <[Omar Elshaer](https://github.com/omarelshaer2)>
* Mohammed Ezzat <[mea800](https://github.com/mea800)>

