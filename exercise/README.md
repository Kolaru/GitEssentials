# Exercises
This folder contain a basic structure that are used in the exercises.

Here is also a summary of the exercises of the workshop.

## Exercise 1
Clone the repo of the workshop.

## Exercise 2
Look at the git history using `git log`.

## Exercise 3
1. Create `exercise/new.txt`
2. Create `exercise/ignore.txt`
3. Modify `exercise/modify.txt`
4. Check their status with `git status`

## Exercise 4
1. Stage the created and modified files from the previous exercise using `git add <filename>`
2. Commit the changes using `git commit -m "<message>"`
3. Check `git status` and `git log`

## Exercise 5
1. Use `git checkout <hash>` to checkout the commit that came before the change you made in exercise 4
2. Check that in your folder you went back to the unmodified state
3. Go back to the latest commit with `git checkout master`

## Exercise 6
1. Merge the exercise branch using `git merge origin/exercise6`
2. Use `git diff` to find out what is now different
> If you see this line it succeeded, nice job

## Exercise 7
1. Merge the exercise branch using `git merge origin/exercise7`
2. If you have done exercise 3, it should have created a conflict
3. Change the conflicting file and save it
4. Commit the file to resolve the conflict
5. Check that you get a clean status with `git status`