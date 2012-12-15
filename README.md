
##aur-helperfunction



Helps managing a local repo of AUR packages



###Provided Functions

##aur-get 

downloads sources for package from AUR

##aur-local-packages 

prints list of installed packages from local repo

`-a` print all packages, including those in repo but not installed

`-e` exclude packages from EXCLUDE variable

##aur-search 

searches packages matching string on AUR

##aur-info 

gets package info from AUR

aur-info [-a] package1 [package2 [...]]

`-a` fills version array

##aur-check 

checks for updates on AUR

`-a` to check every package in repo (including not installed)

`-v` verbose output: prints also packages already up to date

##aur-sobump 

checks for missing dynamic libraries

##repo-upd 

updates local repo adding most recently built packages

##repo-add 

repo-add package.tar.xz

adds package to local repo

##repo-remove 

repo-remove package

removes package from local repo

##makepkg 

wraps makepkg copying most recently built package to local repo
