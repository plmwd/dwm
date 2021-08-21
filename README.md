# dwm
My dwm rice - forked from https://git.suckless.org/dwm.

# Repo Setup
To add the DWM upstream remote, add the following to ./.git/config:
``` ini
[remote "upstream"]
    url = https://git.suckless.org/dwm
    fetch = +refs/heads/*:refs/remotes/upstream/*
    pushurl = DISALLOWED
```

