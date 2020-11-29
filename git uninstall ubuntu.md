# Uninstall git from unbuntu
remove git package from Ubuntu:
```
$ sudo apt-get remove git
```
# Uninstall git and it's dependent packages
remove git package and any other dependant package:
```
$ sudo apt-get remove --auto-remove git
```
### Purging git
delete configuration and/or data files of git:
```
$ sudo apt-get purge git
```
delete configuration and/or data files of git and it's dependencies:
```
$ sudo apt-get purge --auto-remove git
```
