# git

## Configure Git

```sh
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```
## Config editor
```
git config --global core.editor code
```

## Your default branch name
By default Git will create a branch called master when you create a new repository with git init.
```cmd
git config --global init.defaultBranch main
```

## Commit message guidelines
add file

~~~
git init
git add *
git commit -m "Initial commmit"

#Do I need to first create in on github and what url?
git remote add origin [url]
git push origin main
~~~

# GitHub
check if logged in
```
gh auth status
```

login to github
```
gh auth login
```

## using the same github account from multiple pcs
It is best practice to use separate SSH keys on each machine
Is it better to use ssh or tokens?

# GitHub CLI quickstart
Install GitHub CLI on macOS, Windows, or Linux. For more information, see [Installation](https://github.com/cli/cli#installation) in the GitHub CLI repository.
