Installation
=========================

Download repo and add it to your PATH:

```
$ mkdir -p ~/bin
$ export PATH=~/bin:$PATH
$ curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
$ chmod a+x ~/bin/repo
```
You should add the ```export``` to your ```.profile``` or ```.bash_profile```, so that you don't need to execute
it everytime you start developing on the project.


Initializing repo
=========================
```
$ mkdir WORKING_DIRECTORY
$ cd WORKING_DIRECTORY
$ repo init -u https://github.com/hampelratte/vch-repo-manifest.git
```