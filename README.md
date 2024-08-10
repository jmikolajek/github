# github

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

~~~
git init
git add *
git commit -m "Initial commmit"

#Do I need to first create in on github?
git remote add origin [url]
git push origin main
~~~
