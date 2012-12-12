
##aur-helperfunction



Helps managing a local repo of AUR packages



##FUNCTIONS

#aur-get

download sources for package from AUR

#aur-local-packages

print list of installed packages from local repo

-a: print all packages, including those in repo but not installed

-e: exclude packages from EXCLUDE variable

#aur-search 

search packages matching string on AUR

#aur-info

get package info from AUR

aur-info [-a] package1 [package2 [...]]

-a: fill version array

#aur-check 

check for updates on AUR

-a to check every package in repo (including not installed)

-v verbose output: output packages already up to date

#aur-sobump 

check for missing dynamic libraries

#repo-upd

updates local repo adding most recently built packages

#repo-add

repo-add package.tar.xz

add package to local repo

#repo-remove

repo-remove package

remove package from local repo

#makepkg

wraps makepkg copying most recently built package to local repo
