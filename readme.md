# Al's GitHub how-to guide

## Create Local Repo 

* Create a directory to contain the project.
* Go into the new directory.
* Type git init.
* Write some code.
* Type git add .
* Type git commit.

## Add to GitHub 
```
git remote add origin https://github.com/mralc/How-to-use-git-for-hacktoberfest.git
git push -u origin master
```

```
echo "# How-to-use-git-for-hacktoberfest" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/mralc/How-to-use-git-for-hacktoberfest.git
git push -u origin master
```

## Add and commit changes

Make changes to files
```
git add .
git commit
git push -u origin master
```

## Create a branch 
```
git checkout -b altest3
```
make changes
```
git add .
git commit
git checkout master
git push -u origin altest3
```
Go to GitHub and merge the pull request
Download the change to local git
```
git pull
```
