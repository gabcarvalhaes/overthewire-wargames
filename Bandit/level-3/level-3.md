# level-3

## Level Goal

The password for the next level is stored in a file called **spaces in this filename** located in the home directory

## Commands you may need to solve this level

[ls](https://man7.org/linux/man-pages/man1/ls.1.html) , [cd](https://man7.org/linux/man-pages/man1/cd.1p.html) , [cat](https://man7.org/linux/man-pages/man1/cat.1.html) , [file](https://man7.org/linux/man-pages/man1/file.1.html) , [du](https://man7.org/linux/man-pages/man1/du.1.html) , [find](https://man7.org/linux/man-pages/man1/find.1.html)

When we list the content of the server as bandit2, we can see a file with spaces. How do we access it?

![](https://github.com/gabcarvalhaes/overthewire-wargames/blob/master/Bandit/level-3/screenshot-ls-bandit2.png)

We need to use \ in between like this and then we can see the next password:

![](https://github.com/gabcarvalhaes/overthewire-wargames/blob/master/Bandit/level-3/screenshot-cat-spaces.png)

Now we can login to bandit3:

![](https://github.com/gabcarvalhaes/overthewire-wargames/blob/master/Bandit/level-3/screenshot-ssh-bandit3.png)