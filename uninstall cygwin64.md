# uninstalling cydwin64 from win10
### takeown command
which enables an admin to recover access to a file that was previously denied.
/r - recurse through subfolders and files.
/f - file name.
```
takeown /r /f cygwin64
```
### icacls command
capable of displaying and modifying the security descriptors on folders and files.
/t - Apply recursively to existing files and sub-folders
/grant - granting control to everyone
f - full control
```
icacls cygwin64 /t /grant everyone:f
```
### rmdir
removing the complete cygwin64 folder, subfolder and its files
/s - to delete a dir tree
/q -Specifies quiet mode. Does not prompt for confirmation when deleting a directory tree. 
The /q parameter works only if /s is also specified.
```
rmdir /s /q cygwin64 
```
