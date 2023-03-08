# 0. Where am I?

- Write a script that prints the absolute path name of the current working directory.

```

$ ./0-current_working_directory
/root/alx-system_engineering-devops/0x00-shell_basics
$

```

- Display the contents list of your current directory.
```
$ ./1-listit
Applications    Documents   Dropbox Movies Pictures
Desktop Downloads   Library Music Public
$
```

- Write a script that changes the working directory to the user’s home directory.

You are not allowed to use any shell variables
```
julien@ubuntu:/tmp$ pwd
/tmp
julien@ubuntu:/tmp$ echo $HOME
/home/julien
julien@ubuntu:/tmp$ source ./2-bring_me_home
julien@ubuntu:~$ pwd
/home/julien
julien@ubuntu:~$
```
