# Linux Cheatsheet

### Shorten username/directory

- Open .bashrc in editor. You can find it in `~/` directory
- Find following code
```
if [ "$color_prompt" = yes ]; then
    PS1='${debian_chroot:+($debian_chroot)}\[\033[01;32m\]\u@\h\[\033[00m\]:\[\033[01;34m\]\w\[\033[00m\]\$ '
else
    PS1='${debian_chroot:+($debian_chroot)}\u@\h:\w\$ '
fi
```
- Remove `@\h` and replace `w` with `W` like following
```
if [ "$color_prompt" = yes ]; then
    PS1='${debian_chroot:+($debian_chroot)}\[\033[01;32m\]\u\[\033[00m\]:\[\033[01;34m\]\W\[\033[00m\]\$ '
else
    PS1='${debian_chroot:+($debian_chroot)}\u:\W\$ '
```   
- Now reboot bash 
```
$ exec bash
```


- add aliases for git commands
- Find the following lines in .bashrc
```
# some more ls aliases
alias ll='ls -alF'
alias la='ls -A'
alias l='ls -CF'
```

- add the following lines below
```
alias push="git push"
alias commit="git commit"
alias clone="git clone"
```
- reboot bash
```
$ exec bash
```


