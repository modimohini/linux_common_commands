# Linux Common Commands
* find yourself 
``` 
# pwd
>> /users/<user_name>
```
* checklogin #whoami
* change Dir #cd
* List all 
    <details>
        <summary># ls -altr </summary>
        The `ls` command in Linux is used to list directory contents, and when used with the `-altr` options combined, it provides a detailed and specific view of the files in a directory, ordered by modification time. Let's break down what each of these options means:

            - `-a` (`--all`): Lists all entries including those starting with a dot `.`, which are hidden files in Linux. By default, `ls` does not show hidden files.
            
            - `-l`: This option changes the output format to the long listing format. Here, you get detailed information for each file and directory listed, including permissions, number of links, owner, group, size (in bytes), modification date, and time.
            
            - `-t`: Sorts the output by modification time, with the newest files first. By combining this with `-r`, the order is reversed.
            
            - `-r` (`--reverse`): Reverses the order of the file listing. This is useful when combined with `-t`, to list files with the oldest modification time first.

                Putting it all together, `ls -altr` will list all files and directories, including hidden ones, in the long listing format, sorted by modification time, with the oldest entries shown first. This command is particularly useful for viewing the most recently or oldest modified files within a directory, along with detailed information about each file.
</details>

* navigating linux filesystem 
* finding stuff
      * which ls
      * whereis ls
      * find directory optons expression
        >> find / -type f -name apache2
  * serching with locate
  * filtering grep
* modifying files and directories 
  * creating files
  * creating Directories 
  * copying file 
  * renaming file 
  * removing file
  * removing directory
  
  * 