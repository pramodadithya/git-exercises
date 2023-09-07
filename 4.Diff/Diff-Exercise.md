# Git Diff Exercise

This exercise demonstrates the understanding and usage of `git diff`, along with additional practice on creating branches from previous exercise.

## Instructions

### Part 1 - Set up

1. Create a new repository called `git-diff-exercise`.
2. Rename the `master` branch to `current`
3. Add two files `dc.txt` and `marvel.txt`
4. Commit empty files
5. Create a new branch called `1970s`(do not switch to the branch).
6. Add following content to `dc.txt` file in `current` branch

```
World's Finest: Teen Titans (2023)
Batman / Superman: World's Finest (2022)
Dark Knights of Steel (2021)

```

7. Add the following content to `marvel.txt` in `current` branch

```
Daredevil (2022)
Doctor Strange (2023)
Incredible Hulk (2023)
Scarlet Witch (2023)
Avengers (2023)
X-Men: Before The Fall (2023)
Black Panther (2023)
X-Men (2021)
```

8. Stage and commit changes.

9. Add additional lines to `dc.txt` file in `current` branch, stage and commit changes.

```
Knight Terrors: Superman (2023)
Knight Terrors: Zatanna (2023)
Knight Terrors: Detective Comics (2023)
Knight Terrors: Green Lantern (2023)
Knight Terrors: Poison Ivy (2023)
```

10. Switch to `1970s` branch

11. Add following content to `dc.txt` file in `1970s` branch

```
All-Star Western (Volume 2)
Binky (Volume 1)
Hot Wheels (Volume 1)
Super DC Giant (Volume 1)
The Three Mouseketeers (Volume 2)
```

12. Add the following content to `marvel.txt` in `1970s` branch

```
Master of Kung-Fu: “The Death-Day of the Golden Dagger! “
Avengers: “The Korvac Saga”
The Avengers / Defenders War
Iron Man: “Demon in a Bottle”
Avengers: “Kree–Skrull War”
Amazing Spider-Man: “The Night Gwen Stacy Died”
X-Men: “Dark Phoenix Saga”
```

13. Stage and commit changes

14. Check the set up. There should be two branches `current` and `1970s` each branch should contain two files `dc.txt` and `marvel.txt`

### Part 2

1. Compare the difference between the `1970s` branch and the `current` branch across all files.
2. Compare the difference between the `1970s` branch and the `current` branch for only the `dc.txt` file .
3. Switch to `current` branch if not already on it. Run a diff to compare the current `HEAD` to the previous commit.
4. While on the current branch change the `dc.txt` file by replacing `Poison Ivy` with `Batman`. Add `dc.txt` to staging area. DO NOT COMMIT yet.
5. Edit the `marvel.txt` file and add `Spiderman (2099)`. Save the file but do not add to staging area.
6. Run a diff that would reveal the unstaged changes in the working directory (Only the changes in `marvel.txt` should be displayed).
7. Run a diff that would reveal only the staged changes (Only the changes from `dc.txt` should be displayed).
8. Run a diff that prints all changes (staged and unstaged) since the prior commit (changes from both files should be displayed).
