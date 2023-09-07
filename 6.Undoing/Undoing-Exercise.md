# Git Undoing Exercise

This exercise demonstrates the understanding of different ways of undoing things in git and highlights the differences among `restore`,`reset` and `revert`.

## Instructions

## Part 1 - Set up

This section reinforces some of the commands used in previous sections.

1. Create a new folder called `Undoing` and initialize it as a git repository.(Make sure that it is not already in a git repository)

2. Create a file called `timeline.txt`

3. Assume `timeline.txt` indicates a human life. Add the following to file, stage the changes and commit changes with the message "1.birth".

```
Age 0 - New Born
```

4. Add the following to the file , stage the changes and commit changes with the message "2.baby".

```
Age 0-5 - Baby
```

5. Add the following to the file , stage the changes and commit changes with the message "3.Child".

```
Age 6-12 - Child
```

6. Add the following to the file , stage the changes and commit changes with the message "4.Teen".

```
Age 13-19 - Teen
```

7. Add the following to the file , stage the changes and commit changes with the message "5.Youth".

```
Age 20-25 - Youth
```

8. Add the following to the file , stage the changes and commit changes with the message "6.Late 20's".

```
Age 26-30 - Late 20's
```

8. Add the following to the file , stage the changes and commit changes with the message "7.30's".

```
Age 30-40 - 30's
```

9. Add the following to the file , stage the changes and commit changes with the message "8.Middle age".

```
Age 40-50 - Middle age
```

The final file should contain

```
Age 0 - New Born
Age 0-5 - Baby
Age 6-12 - Child
Age 13-19 - Teen
Age 20-25 - Youth
Age 26-30 - Late 20's
Age 30-40 - 30's
Age 40-50 - Middle age

```

## Part 2 - Undoing

1. Check commit history there should be `8 commits` on the `master` branch.

2. Go to the very first commit. this should detach HEAD. Check `timeline.txt`
   to see if the file is back to the first commit.

3. Go back to the commit where the `timeline.txt` contained only till `Teen`. The commit has the message `5.Youth`. Create a new branch called `best-age` based upon this commit.

4. Go back to `master` branch.

5. Delete everything in `timeline.txt` file. save the file.

6. Using a GIT COMMAND (not by undoing in the editor) discard changes made to `timeline.txt` since the last commit. Repeat last step and this step couple of times to practice doing it in different ways.

7. Make your own changes to the `timeline.txt`. Add and commit the changs to the `master` branch.

8. Make more changes to the `timeline.txt`. Add and commit the changes to the `master branch`.

9. You want to keep the master branch clean so move you last two commits to a new branch. In order to acheive this,

   - use the git command to undo the last two commits on the master branch **without losing them from you working direcotry**
   - Create a new branch called `modified`, switch to it, add and commit the changes from your working directory.

10. Switch to the `master` branch and check `timeline.txt` contains the content before it was modified.
