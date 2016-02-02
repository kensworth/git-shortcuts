# git-shortcuts

git-shortcuts is an easily importable bash script to shorten popular git commands.

### Install

To install git-shortcuts for use in Unix/Linux systems, simply navigate to your terminal and run:

```bash
nano ~/.bash_profile
```

Whether or not your system has anything written in this file, append the contents of git-shortcuts.sh to the file, like such:

```bash
#currently within ~/.bash_profile

alias gs="git status"
alias ga="git add"
alias gaa="git add ."
alias grm="git rm"
alias gc="git commit"
alias gcm="git commit -m"
alias gpsom="git push origin master"
alias gpsot="git push origin testing"
alias gplom="git pull origin master"
alias gplot="git pull origin testing"
alias gckt="git checkout testing"
alias gckm="git checkout master"
alias gbr="git branch"
alias grao="git remote add origin"

alias br=". ~/.bash_profile"
alias bp="nano ~/.bash_profile"
```
Then, simply enter `^X` to exit and press `y` when prompted to save. Finally, reload your bash profile with the command `. ~/.bash_profile` and your changes should be set. 

Once executed, subsequent bash editing only requires the shortcut `bp` and reloading only requires a quick `br`. Think of these as acronyms for 'bash profile' and 'bash reload', respectively.

That should be it. Fire away!
