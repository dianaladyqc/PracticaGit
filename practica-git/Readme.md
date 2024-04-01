# GIT

***
Git is a distributed version control system.
***


## Installing on Linux

```shell 
sudo apt install git-all
```


### Check the Installing


```shell
git --version
```


## CONFIGURACTION

### The user name


```shell 
git config --global user.name "lady"
```

### the gmail name

```shell 
git config --global gmail.name "lady@gmail.com"
```


### Check configuration


```
git config --list
```


### Help in git


```shell
git add -h
```

## Getting a Git Repository

- You can take a local directory that is currently not under version control, and turn it into a Git repository, or

- You can clone an existing Git repository from elsewhere.


### Initialize a new repository


```bash
git init
```


## Tracking New Files

```shell
git branch -m main
git status
git add README
git commit -m "mesaje of the commit"

```


***
If you want to see what you’ve staged that will go into your next commit, you can use.
***

```
git diff --staged. 
```



## Viewing the Commit History


```
git log
```

### Specify the format explicitly,


```
git log --pretty=format:"%h - %an, %ar : %s"
```



![Useful specifiers for git log --pretty=format](usefull.png)


