# Notes on Git and Github

Git is free and opensource source control management.

## Installing

Visit [gitwebsite](https://git-scm.com/downloads) and follow download instruction.

## Use Git

### Configuration

These changes are git wide

```
git config --global user.name "Londa Mngadi"
```

```
git config --global user.email "mngadilg@gmail.com"
```

### Using

Making the repo

```
git init
```

Get a status of the repository

```
git status
```

Adding a file to current commit

```
git add <file>
```

Committing 

```
git commit -m "What you've changed" 
```

View what changes were made in file

```
git diff <file>
```

Get list of commits

```
git log --oneline
```

Revert back to the previous hash

The hash can be seen by using git log also use the hash of the change you want to revert not the change you want to revert to.

```
git revert <hash>
```

Clone repository

```
git clone <repository url>
```

Push repository to remote:

You need to have a github account and you have to create a new repo on github.

Changin origin for the repository.

```
git remote add origin <link to repository>
```
Generate a token for accessing repo

Push to repo:

```
git push origin main
```
