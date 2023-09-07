# Git Branching Exercise

This exercise demonstates the ability to

- Create a multiple branch
- Switch between branches using different methods
- Rename a branch
- Delete a branch

## Instructions

1. Make a new folder called `Patronus`.

2. Make a new git repo inside the folder (The folder cannot be in a existing repo).

3. Create a new file called `patronus.txt` (file can be empty for now).

4. Add and commit the file. The commit message should be "add empty patronus file".

5. Make a new branch call `harry` and another branch called `snape` (both should be based on master branch).

6. Move to the harry branch using any of the two ways to change branches.

7. In the `patronus.txt` file, add the following:

```
HARRY'S PATRONUS

        ,/  \.
       |(    )|
  \`-._:,\  /.;_,-'/
   `.\_`\')(`/'_/,'
       )/`.,'\(
       |.    ,|
       :6)  (6;
        \`\ _(\
         \._'; `.___...---..________...------._
          \   |   ,'   .  .     .       .     .`:.
           \`.' .  .         .   .   .     .   . \\
            `.       .   .  \  .   .   ..::: .    ::
              \ .    .  .   ..::::::::''  ':    . ||
               \   `. :. .:'            \  '. .   ;;
                `._  \ ::: ;           _,\  :.  |/(
                   `.`::: /--....---''' \ `. :. :`\`
                    | |:':               \  `. :.\
                    | |' ;                \  (\  .\
                    | |.:                  \  \`.  :
                    |.| |                   ) /  :.|
                    | |.|                  /./   | |
                    |.| |                 / /    | |
                    | | |                /./     |.|
                    ;_;_;              ,'_/      ;_|
                   '-/_(              '--'      /,'



```

8. Add and commit the changes, with the commit message "add harry's patronus".
9. Move to `snape` branch using the alternate way to change branches.
10. Put the following text in the patronus.txt file.

```
SNAPE'S PATRONUS

                   .     _,
                   |`\__/ /
                   \  . .(
                    | __T|
                   /   |
      _.---======='    |
     //               {}
    `|      ,   ,     {}
     \      /___;    ,'
      ) ,-;`    `\  //
     | / (        ;||
     ||`\\        |||
     ||  \\       |||
     )\   )\      )||
     `"   `"      `""

```

11. Add and commit the changes on the `snape` branch with commit message "Add snape's doe patronus".

12. Create new branch upon the `snape` branch called `lily`.

13. Move to lily branch.

14. Edit the `patronus.txt` file so that it says `LILY'S PATRONUS` instead of `SNAPE'S PATRONUS`.

15. Add and commit the change with the message "add lily's doe patronus".

16. Run a git command to list all branches.(The list should contain 4 branches).

17. Create and switch `lily-dup` branch uing one command.

18. Rename `lily-dup` branch to `lily-to-be-deleted`.

19. Delete the `lily-to-be-deleted` branch.
