# **Shell, permissions**

## **Requirements**
* All files will be compiled on Ubuntu 20.04 LTS
* All your scripts should be exactly two lines long ($ wc -l file should print 2)
* A README.md file, at the root of the folder of the project is mandatory
* All your files should end with a new line
* The first line of all your files should be exactly #!/bin/bash
* You are not allowed to use backticks, &&, || or ;
* All your files must be executable

## **Files**
* **_0-iam_betty_**:
Script that switches the current user to the user `betty`.
* **_1-who_am_i_**:
Script that prints the effective username of the current user.
* **_2-groups_**:
Script that prints all the groups the current user is part of.
* **_3-new_owner_**:
Script that changes the owner of the file `hello` to the user `betty`.
* **_4-empty_**:
Script that creates an empty file called `hello`.
* **_5-execute_**:
Script that adds execute permission to the owner of the file `hello`.
* **_6-multiple_permissions_**:
Script that adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello`.
* **_7-everybody_**:
Script that adds execution permission to the owner, the group owner and the other users, to the file `hello`.
* **_8-James_Bond_**: Script that sets the permission to the file `hello` as follows:
  * Owner: no permission at all
  * Group: no permission at all
  * Other users: all the permissions
* **_9-John_Doe_**:
Script that sets the mode of the file `hello` to this:
```
-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
```
    * The file `hello` will be in the working directory
    * You are not allowed to use commas for this script
* **_10-mirror_permissions_**:
Script that sets the mode of the file `hello` the same as `olleh’s` mode.
* **_11-directories_permissions_**:
Script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
* **_12-directory_permissions_**:
Script that creates a directory called `my_dir` with permissions 751 in the working directory.
* **_13-change_group_**:
Script that changes the group owner to `school` for the file `hello`.
* **_14-change_owner_and_group_**:
Script that changes the owner to `vincent` and the group owner to `staff` for all the files and directories in the working directory.
* **_15-symbolic_link_permissions_**: Script that changes the owner and the group owner of `_hello` to `vincent` and `staff` respectively.
  * The file `_hello` is in the working directory
  * The file `_hello` is a symbolic link
* **_16-if_only_**:
Script that changes the owner of the file `hello` to `vincent` only if it is owned by the user `guillaume`.
  * The file hello will be in the working directory 
