# Git Stashing Exercise

This exercise demonstrates the usecase for `git stash`.

## Instructions

1. Initialize a git repo in folder called `Diary`.

2. Create a file called `diary.txt`. Inside the file add the following line.

```
I am the richest person on earth
```

3. Add and commit changes on the `master` branch.

4. Create a new branch called `the-truth`. Switch to it.

5. In the `dairy.txt` file, erase the contents and instead replace it with

```
Not even close.
```

6. Save the file.

7. Switch to `master` branch.
8. The `dairy.txt` file still contains the truth. Stash the changes.
9. The dairy.txt should contain "I am the richest person on earth" again.
10. Add more lies to the `dairy.txt` files:

```
I am the richest person on earth.
I am the smartest person on earth.
I am the happiest person on earth.
I can fly.
```

11. Add and commit changes to the `master` branch.
12. Switch over to `the-truth` branch.
13. Retrieve the earlier changes that were stashed.
14. Add more truth

```
Not even close but
I can be the richest person on earth.
I can be the smartest person on earth.
I can be the happiest person on earth.
I can even fly.
if I put my mind to it.
```

14. Add and commit the changes on `the-truth` branch
