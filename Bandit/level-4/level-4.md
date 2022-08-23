level-4

## Level Goal

The password for the next level is stored in a hidden file in the **inhere** directory.

## Commands you may need to solve this level

[ls](https://man7.org/linux/man-pages/man1/ls.1.html) , [cd](https://man7.org/linux/man-pages/man1/cd.1p.html) , [cat](https://man7.org/linux/man-pages/man1/cat.1.html) , [file](https://man7.org/linux/man-pages/man1/file.1.html) , [du](https://man7.org/linux/man-pages/man1/du.1.html) , [find](https://man7.org/linux/man-pages/man1/find.1.html)

If we simply use "ls" to list the contents of this user directory, nothing shows up. We need to use the option "-a" to show hidden contents. And now it shows a file which stores the password for the user bandit4:
![]((https://github.com/gabcarvalhaes/overthewire-wargames/blob/master/Bandit/level-4/screenshot-ls-hidden-bandit4.png)

Then we can use the password to login to bandit4:
![]((https://github.com/gabcarvalhaes/overthewire-wargames/blob/master/Bandit/level-4/screenshot-ssh-bandit4.png)