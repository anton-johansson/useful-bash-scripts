# Git

Utilities to work with Git.


## Multiple Git configurations

First, set up the template folder for Git projects:

```sh
$ mkdir ~/.git_template
$ git config --global init.templatedir '~/.git_template'
```

Then, configure the email to a dummy-email (must be the exact same as below):

```sh
$ git config --global user.email 'not-configured'
```

Then, create a [`pre-commit`](pre-commit) hook (`~/.git_template/hooks/pre-commit`) and make it executable:

```sh
$ chmod +x ~/.git_template/hooks/pre-commit
```

Also do not forget to re-initialize your repositories!

```sh
$ git init
```
