
#aur-helperfunction



Provides bash functions which help managing a local repo of AUR packages



#Provided Functions

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

`-a` fills version array (if run as standalone, declare it with "local -A aurversion aurmaint" beforehand)

##aur-check 

checks for updates on AUR

`-a` to check every package in repo (including not installed)

`-v` verbose output: prints also packages already up to date

if packagenames are provided after options, check those in spite of local repo

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
