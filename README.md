This is heavily based on (ugh...where did I cobble this from...to be updated)
It utilizes https://github.com/josephwecker/bashrc_dispatch to allow cross-platform configurations.

# shell-files

I manage my shell files using vcsh, which is a super-cool way to have multiple git repos inside the same directory. It works nicely on both OS X and Linux.

Here's how I set mine up.
```
vcsh init shell-files
vcsh enter shell-files
git remote add origin https://github.com/[your repo]/shell-files.git
move any old .bash* out of the way
git pull -u origin master
exit
```


