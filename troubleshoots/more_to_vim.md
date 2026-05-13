One interesting troubleshoot I got is, if lets say a shell is converted intosome nasty looking thing which is obviously not a shell. Then how do we login to it without administrative preveileges?

There was the showtext script where it just executes the more command and exits with 0. So, we know if we smaller the size of the terminal then we can actually get in the more without being kicked out. In more there are several options to execute like v to open the file in vim. I did the same thing, and after entering into vim i just explored the file bandit_pass/bandit26 to get the file. As simple as that :) . Now to going back to the shell will lead to more command because the script showtext is acting as the default shell. So what to do is, again in vim there is a command to actually override the shell. 

```vim
:set shell=/bin/bash in command mode
```
with this we can login into bash shell and do the next level.
