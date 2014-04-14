alias
=====

My personal shell. It's used to add linux and mac os shell aliases.

If you want to add this config to your system. just paste the shell below into ~/.bashrc or ~/.bash_profile

```
 if [ -f ~/.bash_aliases ]; then
     . ~/.bash_aliases
 fi
```

Then you should do on terminal in project folder

```
ln -s bash_aliases_[Platform] ~/.bash_aliases
```

