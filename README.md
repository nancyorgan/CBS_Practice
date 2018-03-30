# CBS Practice
This is documentation of Sarah and Nancy's pilot GitHub project

### Basic navigating, adding, and pushing
```
$ cd your_directory_here
$ ls
$ git add .
$ git status
$ gitcommit -m "I made an edit. Yay."
$ git push
```

### Pulling from master
```
$ git pull origin master
```

### Dealing with merge conflicts 
- Do a pull
- Manage conflicts 
- Remove markers of the conflicts (>>>> and ======) 
- Push again 

### Creating a branch
```
$ git checkout -b branch-name
$ git add . 
$ git commit -m "your message"
$ git push origin branch-name
```
### Returning to the master to make a commit
```
$ git checkout master
$ git pull the-branch-you-want-t-pull-from
$ git add .
$ git commit -m "your message"
$ git push origin master
```

### To check which branch you're on:
``` 
$ git branch
```
The starred repo is the current one. 

#### When you forgot to pull 
press "i"
write your merge message
press "esc"
write ":wq"
then press ent

## Committing a branch file to the master:
https://www.sap.com/developer/tutorials/webide-github-merge-pull-request.html

## Upcoming to-dos
- Private repos? 




