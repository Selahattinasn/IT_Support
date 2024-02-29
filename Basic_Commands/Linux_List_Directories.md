```Bash
ls
ls /
ls -l
ls -la
ls --help
man ls
```


In Linux, the main directory that all others stem
from is called the root directory. The path to the root directory is
denoted by a slash or forward slash. An example of a path in Linux that
starts from the root directory is /home/cindy/Desktop,
just like C backslash users, backslash, cindy backslash
Desktop in Windows. Let's go ahead and
see what's under the root directory. We're going to be using the ls or
list directory contents command. We also want to give this command, the
path of the directory that we want to see. If we don't provide a path it'll just
default to the current directory we're in. So ls/. All right. Now, we can see all the directories that
are listed under the root directory. There are a lot of directories here and
they're all used for different purposes. We won't go through them all. But let's talk about a few
of the important ones. 

/bin, this directory stores our
essential binaries or programs. The ls command that we
just used is a program and it's located here in the /bin folder. It's very similar to our Windows
program files directory. 

/etc, this folder stores some pretty
important system configuration files 

/home. This is the personal directory for users. It holds user documents, pictures and etc. It's also similar to our
Windows users directory. 

/proc, this directory contains information
about currently running processes. We'll talk more about processes
in an upcoming lesson. 

/user, the user directory doesn't
actually contain our user files like our home directory. 
It's meant for user installed software. 

/var, we store our system logs and basically any file that
constantly changes in here. The ls command has a couple of very
useful flags that we can use too. Similar to Windows commands parameters, a flag is a way to specify
additional options for a command. We can usually specify
a flag by using a hyphen. Then the flag option. This varies depending
on the program though. 

Every command has different flag options. You can actually view what
options are available for a command by adding the --help flag. Let's see this in action. There's an incoming wall of text but
don't panic. You don't have to memorize these options. This is mainly used for reference. For now, let's just quickly
go through the help menu. At the top here it tells you what
format to put the command in. And here it gives you a description
of what the command does. This huge chunk of text lists
the options that we can use. It tells us what command flags
are available and what they do, the --help flag is super useful and even experienced
OS users refer to it every so often. Another method that you can use to get
information about commands is the man command for manual. It's used to show us manual pages. In Linux, we call them man pages. To use this command, just run man
then the command you want to look up. So let's look up man ls and here we get the same
information as --help, but with a little more detail, okay. Back to using the ls command. Right now,
it's not quite friendly to read. So let's make our directory list more
readable with the -l flag for long. This shows detailed
information about files and folders in the format of a long list. Now, we can see additional information
about our directory and the files and folders in them. Similar to the windows show properties, the ls command will show us
the detailed file information. Let's break down this output
starting from the left. The first column here
are file permissions. Okay, next up is the number
of links a file has. Next, we have the file owner,
then the group the file belongs to. Groups are another way
we can specify access. So then we have the file size,
the time stamp of last modification. And finally the file or directory name. The last flag that we'll discuss for
the ls command is the -a or all option. This shows us all the files in
the directory, including the hidden files. You'll notice that I appended
two different flags together. This is the same thing as ls -l
-a/ both work the exact same way. The order of the flag determines
which order it goes in. In our case, it doesn't matter if we do
a long list first or show all files first. Check out how there are some new files
that are visible when we use this flag. The -a or all flag shows all
files including hidden ones. You can hide a file or
directory by pre pending a dot to it. Like the file shown here dot I am hidden. We've covered a lot in this video. We learned how to view detailed
information about files with the ls command. We also started using computer paths and we learned how to get help with commands
using the --help flag and man pages. We even took a sneak peek
at our Linux file system.