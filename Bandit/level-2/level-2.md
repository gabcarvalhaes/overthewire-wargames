# level-2

## Level Goal

The password for the next level is stored in a file called **-** located in the home directory

## Commands you may need to solve this level

[ls](https://man7.org/linux/man-pages/man1/ls.1.html) , [cd](https://man7.org/linux/man-pages/man1/cd.1p.html) , [cat](https://man7.org/linux/man-pages/man1/cat.1.html) , [file](https://man7.org/linux/man-pages/man1/file.1.html) , [du](https://man7.org/linux/man-pages/man1/du.1.html) , [find](https://man7.org/linux/man-pages/man1/find.1.html)


When we list the content of the server now, it shows a file named "-". It is a dashed filename. We can't simply use "cat -" to open the file. We need to use an operator:
![[Pasted image 20220821162706.png]]

And then, we can login to bandit2:
![[Pasted image 20220821162852.png]]