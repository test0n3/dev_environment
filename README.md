# List of action to prepare a dev environment in a new machine

## Global `.gitignore`

Description: https://gist.github.com/subfuzion/db7f57fff2fb6998a16c
First create the global gitignore file then:

```
git config --global core.excludesfile ~/.gitignore
```

add relevant subdirectories and files

```
.directory
npm-debug.log
.DS_Store
Thumbs.db
.idea/
log/
*.log
node_modules/
```

## Reuse ssh files

Files are saved in `~/.ssh` usually of the name:

```
id_rsa
id_rsa.pub
```

but if one has many git accounts (many accounts in Github, Gitlabs, bitbucket), the following procedure might be useful: https://medium.com/@pinglinh/how-to-have-2-github-accounts-on-one-machine-windows-69b5b4c5b14e
