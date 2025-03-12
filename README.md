# sheetcheat
Sheet cheat for all nice commands I find in my career for many different tools.

## vim

Change indent from 4 to 2 spaces in the hole file:

```vim
%s;^\(\s\+\);\=repeat(' ', len(submatch(0))/2);g
```
