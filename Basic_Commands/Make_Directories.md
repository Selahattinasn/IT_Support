```PowerShell
mkdir my_cool_folder
```

+ to name a directory_name wit spaces , we have to ways, 
1. surround the name with quotos; 
2. using escape characters; escape character in lnux is "\" in windiws is " ' ". 
```PowerShell
mkdir "my cool folder"
mkdir my´ coll` folder 
```

```Bash
mkdir my_cool_folder
mkdir "my cool folder"
mkdir my\ coll\ folder
```

Now that we've covered listing and changing directories, let's learn how to add new directories. We can do this in the GUI in a super simple way. Just right-click New, then Folder, and bam, you have a new folder. Now what if we wanted to do this in the CLI? In PowerShell, the command to make a new directory is called mkdir or make directory. Let's make a new directory called my_cool_folder, there it is. That was easy. 

What if we wanted to use spaces in our folder name instead of underscores? What do you think would happen if I did this instead? Mkdir my cool folder, that's an error. 

Mkdir is trying to interpret cool and folder as other parameters to the mkdir command, it doesn't understand those words is valid parameters. 

Turns out that our shell doesn't interpret spaces the way we do. We need to tell it explicitly that this folder name is one single thing. We can do this in a variety of ways. We can surround the name with quotes, like mkdir, my cool folder, or we can escape the space by using the back tick character mkdir. 

My back tick, cool back tick folder. Escaping characters is a pretty common concept when dealing with code. It means that the next character after the back tick should be treated literally. In our example, escaping the space tells the shell that the space after the back tick is part of our filename. While the back tick is the escape character and PowerShell, other shells and programming languages may use another character as an escape character.