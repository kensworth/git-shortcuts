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

### Commands

All of the shortcuts here are simply acronyms or shortenings for popular git commands. For example, `git status` becomes `gs`, and more lengthy commands such as `git push origin master` becomes `gpsom`. A full list of shortcuts can be found here:

`git remote add origin`: `grao`
`git status`: `gs`
`git add`: `ga`
`git add .`: `gaa`
`git rm`: `grm`
`git commit`: `gc`
`git commit -m`: `gcm`
`git push`: `gps`
`git push origin`: `gpso`
`git push origin master`: `gpsom`
`git pull`: `gpl`
`git pull origin`: `gplo`
`git pull origin master`: `gplom`
`git branch`: `gbr`


These commands look funky, but will become second nature, I promise. The beauty here is that you can follow the simple system of bash aliasing that I've used above to help yourself create your own shortcuts. Happy bashing!
