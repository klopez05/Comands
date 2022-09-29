# Intall git

If you have git on the Ubuntu, you can confirm that this is the casse for the server with the following command:

```
$ git --version
```

if you get output similar to the foolowing, Git is already installed

> Output
> git version 2.25.1

If you didn't get a Git version number back, you can install it with Ubuntu's default APT package manager.
First, use the apt package management tools to update your local package index.

```
$ sudo apt update
```
After the update is complete, you can install git.

```
$ sudo apt install git
```

To confirm taht you istalled Git successfully, run the following command and verify that you receive revelant output.

```
$ git --version
```
> Output
> git version 2.25.1
