The command line interfaces or CLIs available on Windows are: 

+ Command Prompt: cmd.exe
+ Power Shell   : powershell.exe

 Many PowerShell commands that we'll use are actually aliases for common commands in other shells. An alias is sort of like a nickname for a command.

The C drive is where the Windows operating system is installed.

ls command list directories under working-directory. For example : The C drive root folder is what we call a parent directory and the contents inside are considered child directories. Parents and children are common terms that stand for hierarchical relationships in OSs. 

![ls_command](images/ls_command.png)

to get information about and examples of a comand we use ***Get_Help*** command. The syntax/usage is:

```PowerShell
Get-Help ls 
```
This will give us a brief summary of the command's parameters. But if you want to see more detailed help, try Get-Help ls -Full.

```PowerShell
Get-Help ls -Full
```

To see all the hidden files in this directory, we can use another useful parameter for the ls command, -Force.

```PowerShell
ls -Force C:\
```
