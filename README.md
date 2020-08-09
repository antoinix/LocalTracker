## ntrack

### I. What is <u>ntrack</u>?
#### 1. ntrack( Nerd Tracker ), a simple local file and git repo tracker.
#### 2. For file tracking, ntrack focuses on abs path instead of inode.
#### 3. For git repo tracking, ntrack searches in $HOME/ by default.
---
### II. How to <u>use</u> ntrack?
#### 1. clone this git repo to local:
```
git clone --depth=1 https://github.com/antoinix/ntrack
```
#### 2. run <i>configure</i>, an automatic configuration shell script.
```
cd ntrack && ./configure
```
##### Note: ntrack will be moved to /usr/bin, so you need to enter the password for current user
#### 3. use '-h' option to view detailed help information
```
ntrack -h
```
---
### III. How to <u>configure</u> ntrack?
#### 1. The path of configuration file is $HOME/.config/ntrack/ntrack.conf
#### 2. The variables and functions that can be modified by ntrack.conf so far are written in it.
#### 3. In addition, you can even modify the source code.
---
### VI. Why ntrack?
#### 1. For file tracking, ntrack can help us save much time to track the status of specific files everywhere in local
#### 2. For git repo tracking, ntrack can find local git repo  in \$HOME except some ignored directory you specified
#### 3. ntrack is a simple shell script. It is easy to use, easy to understand, easy to configure and even easy to modify
