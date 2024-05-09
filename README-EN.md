# bash-scripts

A repository with simple and useful shell scripts which can be easily installed in your linux OS

## How to Use

First clone the repo with ```git clone <url>```

There's a main file named "doLinks" which creates symbolic links of all scripts of this repo in the folder $HOME/bin

Check if this folder has already been created and included on the PATH

Run it which super-user permission(sudo)

If it hasn't been created yet, do the following:

```
mkdir $HOME/bin
export PATH="$HOME/bin:$PATH"
source $HOME/.bashrc
```
once it has been created, just run doLinks, and you be ready to run these scripts

Below you'll find a summary of all the scripts contained in this repo

### Simple Project

Creates a HTML,CSS,JS simple project in the specified path

```
simpleProject -d "./destination" -n "name"
```
