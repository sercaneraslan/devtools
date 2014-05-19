Alias'lar
========

### OPEN

```
vim ~/.bash_profile
```

### ADD

```
alias a='git add .'
alias b='git branch'
alias bb='git checkout -'
alias c='git checkout'
alias ci='git commit -am'
alias cx='clear'
alias d='git diff master -w --color'
alias dd='git diff'
alias df='git diff master -- '*.js' '*.css' '*.html''
alias ff='git ls-files'
alias g='git grep'
alias l='git log -p'
alias m='git checkout master'
alias mm='git merge master'
alias mb='git merge'
alias mmd='git branch --merged master | grep -v 'master$' | xargs git branch -d'
alias n='git diff master --name-only'
alias p='git pull'
alias pp='git push'
alias rst='git reset --hard'
alias s='git status'

alias gr='grunt'
alias grw='grunt watch'

alias v='vim'
alias ss="'/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl'"
```

### RUN

```
. ~/.bash_profile
```
