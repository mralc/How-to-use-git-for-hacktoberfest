# Al Guide how to git hub

## Create Local Respo 


* Create a directory to contain the project.
* Go into the new directory.
* Type git init.
* Write some code.
* Type git add .
* Type git commit.

## Add to git hub 
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

## Add commit changes

Make changes to files
```
git add .
git commit
git push -u origin master
```

## create a branch 
```
git checkout -b altest3
```
makes changes
```
git add .
git commit
git checkout master
git push -u origin altest3
```
Go to git hub and merge the pull reguest
Download the change to local git
```
git pull
```