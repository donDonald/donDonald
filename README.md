<div align="center">
    <img src="images/license-MIT-blue.svg">
</div>




# Hi there 👋

# donDonald repo
Collecting all repos for donDonald




### Install repo tool
```
$ mkdir -p ~/bin
$ curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
$ chmod a+x ~/bin/repo
$ export PATH=~/bin:$PATH
```




### Clone respositories over http
```
$ mkdir donDonald && cd donDonald
$ repo init -v -u https://github.com/donDonald/donDonald.git -b main
$ repo sync
```




### Clone respositories over ssh
```
$ mkdir donDonald && cd donDonald
$ repo init -v -u git@github.com:donDonald/donDonald.git -b main
$ repo sync
```
