# Git Basics Exercise

This exercise demonstates the ability to

- initialize a local git repository
- add content to the repository
- move content to the staging area
- commit changes with appropriate message
- check logs
- remove content

## Instructions

1. Create a new folder called `Shopping`.
2. Initialize a new git repo inside `Shopping` folder (Make sure `Shopping` folder is not in a existing git repo).
3. Make a new file called `yard.txt`.
4. Make another file called `groceries.txt`.
5. Make a commit that includes both empty files. The meesage should be `create yard and groceries lists`.
6. In the `yard.txt` file, add the following changes.

```

- 2 bags of potting soil
- 1 bag of worm castings

```

7.  In the `groceries.txt` file add the following:

```
- 4 tomatoes
- 6 shallots
- 1 fennel bulb
```

8.  Make a new commit, including **ONLY the changes from the `groceries.txt` file**. The commit message should be "add ingredients for tomato soup".
9.  Make a second commit including **ONLY the changes to the `yard.txt` file**. The commit message for this commit should be "add items needed to garden box".
10. Add the following line to the `yard.txt`

```
- couple of seed potatoes
```

11. In the garden.txt file, change the first line from "2 bags of potting soil" to "3 bags of potting soil".

```
- 3 bags of potting soil
- 1 bag of worm castings
```

12. Make a commit that includes the changes to BOTH files. The commit message should be "add items needed to grow potatoes".

13. Use git command to display the list of the commits. There should be 4 commits.

14. Create a temporary file called "remove-me.txt". add the file to staging area. commit the changes with message "File to be removed later".

15. Remove "remove-me.txt" file, add the change to staging area and commit changes with the message "Removed the file as required",

16. Display list of commits. There should be 6 commits.
