# git-bash-custom
This is a quick tutorial on how to customize Git Bash

# Clean input prompt
If you want to have a prompt like this: `name@lastname:~$` instead of the defalult `user@host MINGw64 ~` you need to modify the *etc/profile.d/git-promt.sh* file:
```sh
PS1="$PS1"'\name@lastname'      # user@host<space> "$PS1"'\u@\h '
#PS1="$PS1"'\[\033[35m\]'       # change to purple
#PS1="$PS1"'$MSYSTEM '          # show MSYSTEM

...

PS1="$PS1"                      # new line $PS1"'\n'
```

# Run Python
In the users home directory type:
```sh
echo "alias python='winpty python.exe'" >> ~/.bashrc
```
