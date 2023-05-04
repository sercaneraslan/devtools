## Terminal
I prefer [iTerm2](https://iterm2.com) as a terminal and [Oh My ZSH](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH) as a shell.

## Aliases
You can find my aliases below, which I use often.

```
# Alias
alias b='git branch'
alias bb='git checkout -'
alias c='git checkout'
alias ci='git commit -am'
alias cx='clear'
alias d='git diff master -w --color'
alias dd='git diff'
alias ff='git ls-files |grep '
alias ga='git add .'
alias g='git grep'
alias l='git log -p'
alias m='git checkout master'
alias mm='git merge master'
alias mb='git merge'
alias n='git diff master --name-only'
alias p='git pull'
alias pp='git push'
alias rst='git reset --hard'
alias s='git status'
alias sl='git shortlog -s'
alias sln='git shortlog -s -n'
alias st='git stash'
alias sp='git stash pop'

alias ni='npm install'
alias ns='npm run start'
alias nb='npm run build'
alias yi='yarn install'
alias ys='yarn start'
alias yb='yarn build'

alias v='vim'
alias ss="'/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl'"

alias bp='vim ~/.bash_profile'
alias bpr='. ~/.bash_profile'

alias yv='sudo chown -R sercaneraslan:wheel'

alias de='cd ~/Desktop/'
```

#### How do I add these aliases?

* Open .bash_profile: `vim ~/.bash_profile`
* Add all of them to the end of the file.
* Save .bash_profile.
* Execute .bash_profile: `. ~/.bash_profile`
* Close your terminal and open it again.

If it doesn't work, open the .zshrc file via this command `vim ~/.zshrc` and add `source ~/.bash_profile` line to the end of the file. After that, close your terminal and open it again.

## Themes

I prefer `minimal` theme. (You can select your [theme](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes))

#### How do I change my theme?

* Open .bash_profile: `vim ~/.bash_profile`
* Find the `BASH_IT_THEME='bobby'` line and change it.
* Save .bash_profile.
* Execute .bash_profile: `. ~/.bash_profile`
* Close your terminal and open it again.
