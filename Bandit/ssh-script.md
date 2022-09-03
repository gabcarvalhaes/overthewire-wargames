# SSH script 



Since I have to login a lot in this wargame, I wrote a bash script to help me gain some time.

In order to use the script, you need to install sshpass and store the passwords in .txt files. 

```bash
#!/bin/bash

if ["$1" == ""] || ["$2" == ""]
then
		echo "Usage: "$0" pass.txt usernumber"
		echo "Example: "$0" bandit1password.txt 1"
else
		sshpass -f "$1" ssh bandit"$2"@bandit.labs.overthewire.org -p2220
fi
```

