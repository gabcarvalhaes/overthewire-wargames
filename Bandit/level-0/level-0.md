# level-0

Completing this level only requires you to connect to bandit.labs.overthewire.org through ssh. The username is **bandit0** and the password is **bandit0**.

We can login using only ssh like this:
```Bash
> ssh bandit0@bandit.labs.overthewire.org -p2220
```

But we can also login using sshpass for the password in a single command line:
```Bash
> sshpass -p "bandit0" ssh bandit0@bandit.labs.overthewire.org -p2220
```

This way, with only one line, we can login to the server;
