learning about shell permissions

Notes on task 11-directories_permission:
	-The find command finds all subdirectories of the current 
	directory and the -type d option restricts the search to only 
	directories. The -exec option runs the chmod command on each of 
	the directories found, adding execute permission for the owner,
	group, and others.

	-The 755 argument to chmod sets the permissions to rwxr-xr-x, 
	which means the owner has read, write and execute permission, 
	the group and others have read and execute permission.

	-Regular files will not be affected because the -type d option 
	specifies that only directories should be operated on.
