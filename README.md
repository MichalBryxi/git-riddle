# git-riddle

The task is:

1) Open both `*.txt` files in your favourite IDE and edit them.
2) Now you should see:
```sh
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   bar.txt
	modified:   foo.txt

no changes added to commit (use "git add" and/or "git commit -a")
```
3) Check that you can run:
```sh
$ git add foo.txt
```
4) Now figure out why following gives you error:
```sh
$ git add bar.txt
fatal: pathspec 'bar.txt' did not match any files
```