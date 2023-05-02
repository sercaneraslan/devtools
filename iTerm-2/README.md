Bash it Kurulumu
========

1. Kurulu değilse Xcode'u kurun.
2. Repoyu klonlayınız: `git clone https://github.com/revans/bash-it.git ~/.bash_it`
3. `~/.bash_it/install.sh` komutunu çalıştırınız (`~/.bash_profile` dosyanız otomatik olarak yedeklenecek).
4. Sorulara cevap veriniz.
5. iTerm'i kapatıp açınız.

Bash it Genel Ayarlar
========

* `.bash_profile` dosyası açılır.

```
vim ~/.bash_profile
```

* Alias'lar için dosyanın sonuna aşağıdaki eklemeler yapılır.

```
# Alias
alias b='git branch'
alias bb='git checkout -'
alias c='git checkout'
alias ci='git commit -am'
alias cx='clear'
alias d='git diff master -w --color'
alias dd='git diff'
alias df='git diff master -- '*.js' '*.css' '*.html''
alias ff='git ls-files |grep '
alias ga='git add .'
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
alias sl='git shortlog -s'
alias sln='git shortlog -s -n'
alias st='git stash'
alias sp='git stash pop'

alias gr='grunt'
alias grl='grunt live'
alias gbi='grunt bower:install'
alias ggp='grunt github-pages'

alias ni='npm install'

alias v='vim'
alias ss="'/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl'"

alias yv='sudo chown -R sercaneraslan:wheel'

alias bp='vim ~/.bash_profile'
alias bpr='. ~/.bash_profile'

alias de='cd ~/Desktop/'
```

* Fonksiyonlar için aşağıdaki eklemeler yapılır.

```
# Functions

function gi {
    npm install --save-dev "$1"
}
```

* Tema değiştirmek için export `BASH_IT_THEME='bobby'` yazan satır bulunur, istenilen tema seçilir. (Temalar için: [temalar](https://github.com/revans/bash-it/wiki/Themes) )

```
BASH_IT_THEME='minimal'
```

* `.bash_profile` dosyası çalıştırılır.

```
. ~/.bash_profile
```

* Son olarak iTerm kapatılıp yeniden açılır.
