# git
[] - optional, <> - mandatory
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
git remote add origin [url]  # is [] correct or should it be <>
git push origin main
~~~

### Downloading a repository
```
git clone [url] how do it works
```
> ❤️ TO DO git clone docs
> test
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
```gh auth login```
GitHub CLI automatically stores your Git credentials for you when you choose HTTPS as your preferred protocol for Git operations and answer "yes" to the prompt asking if you would like to authenticate to Git with your GitHub credentials. This can be useful as it allows you to use Git commands like git push and git pull without needing to set up a separate credential manager or use SSH.

```gh status```

## Creating a repository
```
gh repo create
gh repo create organisation_name/repository_name
```



to understand

gh repo fork

## Install
vs code\
git\
github cli, desktop\
sourcetree

[Creating a fine-grained personal access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#creating-a-fine-grained-personal-access-token)
