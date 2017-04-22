# hello-github
github getting started for students

To clone this repository open git bash and type:

git clone https://github.com/alberto-pelosi/hello-github.git

Now that repository is cloned, change README.md and try to commit it.

Before you have to stage the files you want to commit, so type:
```
git add README.md
```
Now you can commit:
```
git commit -m "This is the commit message"

```
To improve team-work it is important to write meaningful commit messages.

Commit command sends your changes to your local repository.

If you want to push them on remote repository type:
```
git push origin master

```
Where origin is the name of you remote repository and master is the branch.

If another developer pushes its changes on remote repository, you can pull them with:
```
git pull origin master

```
To create a branch type:
```
git branch myfirstbranch

```
Then modify README.md and commit changes with:

```
git add README.md

```
```
git commit -m "This is my first branch commit"

```
And then push it with:

git push -u

