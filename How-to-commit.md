# How to commit
For commiting your changes you have to do these steps, provided that you're using a shell:

1. Create once your own branch
> git checkout -b [branchname]

2. Add all new files
> git add .

3. Commit your changes to your locall Repository and write a small message what you've downloaded
> git commit -am "[your-message]"

4. Pull (fetch + merge) the current master from github to be sure that you have the last version
> git pull origin master

5. If neccessary solve merge-conflicts

6. push your local branch to github
> git push origin [branchname]

7. Checkout to your local master
> git checkout master

8. Get the current master
> git pull origin master

9. If neccessary solve merge-conflicts

10. Merge your branch into master
> git merge origin [branchname]

11. Push your local master to github
> git push origin master

12. Switch to your branch
> git checkout [branchname]

## CheatSheet
**[value]** a value you have to add. Syntax is without braces.

Repository localtions at example master:
* **master** - the localmaster on your machine
* **origin master** - the master on github
