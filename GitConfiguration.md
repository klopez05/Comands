# Git Configuration

Once you're happy with your Git version, you should configure Git so that the commit messages it generates contain the correct information and support you as you build your software project.

This configuration is possible if we apply the command `git config`, for example

```
$ git config --global user.name "Your name"
$ git config --global user.email "Your email"
```

We can see all the configuration elements created by typing the following::

```
$ git config --list
```

>Output
>user.name=`Your name`
>user.email=`Your email`
