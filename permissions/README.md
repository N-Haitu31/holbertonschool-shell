Shell, permissions

0-iam_betty : script that switches the current user to the user betty.

1-who_am_i : script that prints the effective username of the current user.

2-groups : script that prints all the groups the current user is part of.

3-new_owner : changes the owner of the file hello to the user betty.

4-empty : script that creates an empty file.

5-execute : script that adds execute permission to the owner of the file.

6-multiple_permissions : adds execute permission to the owner and the group owner, and read permission to other users, to the file.

7-everybody : adds execution permission to the owner, the group owner and the other users, to the file.

8-James_Bond : script that sets the permission to the file with No permission u+g but all to o.

9-John_Doe : -rwxr-x-wx to the file hello.

10-mirror_permissions : script that sets the mode of the file hello the same as olleh s mode.

11-directories_permissions : script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.

12-directory_permissions : script that creates a directory called my_dir with permissions 751 in the working directory.

13-change_group : script that changes the group owner to school for the file hello.

14-change_owner_and_group : script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

15-symbolic_link_permissions : script that changes the owner and the group owner of _hello to vincent and staff respectively.

16-if_only : script that changes the owner of the file hello to vincent only if it is owned by the user guillaume.
